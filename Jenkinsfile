pipeline {
    agent any

    stages {
        stage('Checkout GIT') {
            steps {
                echo 'Pulling...'
                checkout scm
            }
        }

        stage('Date système') {
            steps {
                sh 'date'
            }
        }
    }
}
