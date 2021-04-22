pipeline {
  agent any
  stages {
    stage('ini') {
      steps {
        sh 'docker -v'
      }
    }

    stage('get version') {
      steps {
        sh 'docker version'
      }
    }

  }
}