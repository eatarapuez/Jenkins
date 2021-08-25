pipeline {
  agent any
  stages {
    stage('scm git') {
      steps {
        bat(returnStdout: true, script: 'ipconfig')
      }
    }

    stage('aprobacion') {
      steps {
        input 'desea avanzar'
      }
    }

  }
  environment {
    data = '/usr/bin/local'
  }
}