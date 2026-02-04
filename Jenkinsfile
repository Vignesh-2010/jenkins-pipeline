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

   pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build in progress...'
            }
        }
    }

    post {
        success {
            echo 'BUILD SUCCESSFUL: Pipeline completed without errors'
        }
        failure {
            echo 'BUILD FAILED: Please check the logs'
        }
    }
}
}
