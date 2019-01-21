pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        bat(script: 'calc', encoding: 'calc', label: 'calc', returnStatus: true)
      }
    }
    stage('soobsh') {
      steps {
        echo 'NORM'
      }
    }
  }
}