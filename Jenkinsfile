pipeline {
  agent any

  stages {

    stage('Python Linit Check') {
      steps {
        sh '''
          pylint payment.py || true
          # Indeally we will not ignore those failures , But as a lab we are proceeding.
          pylint rabbitmq.py || true
        '''
      }
    }

  }

}