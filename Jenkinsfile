pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/chandrs/pipeline-examples.git', branch: 'master', changelog: true, poll: true)
      }
    }
  }
}