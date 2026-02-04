pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout stage'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage'
            }
        }
    }

    post {
        success {
            echo 'BUILD SUCCESS: All stages completed successfully'
        }
        failure {
            echo 'BUILD FAILED: Please check logs for errors'
        }
        always {
            echo 'POST ACTION: Pipeline execution finished'
        }
    }
}
