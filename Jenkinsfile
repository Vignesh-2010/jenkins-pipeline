pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checked out from Git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build started'
                echo 'Hello from Jenkins Pipeline'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully from Git'
        }
        failure {
            echo 'Pipeline failed'
        }
    }
}
