pipeline {
    agent any


    stages {
        stage('Python Lint Check') {
            steps {
                sh '''
                    pylint payment.py
                    pylint rabbitmq.py
                '''
            }

        }


    }

}