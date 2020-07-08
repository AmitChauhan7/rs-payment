pipeline {
  agent any

  stages {

    stage('Python Linit Check') {
      steps {
        sh '''
          pylint payment.py || true
          pylint rabbitmq.py || true
        '''
      }
    }

  }

}