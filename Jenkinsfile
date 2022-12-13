pipeline {
  agent any
  stages {
    stage('test1') {
      steps {
        echo 'this is a test pipeline'
        bat(script: 'date', returnStatus: true)
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}