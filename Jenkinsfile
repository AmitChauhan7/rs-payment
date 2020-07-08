pipeline {
  agent any

  stages {

    stage('Python Linit Check') {
      steps {
        sh '''
          pylint payment.py
          pylint rabbitmq.py
        '''
      }
    }

  }

}