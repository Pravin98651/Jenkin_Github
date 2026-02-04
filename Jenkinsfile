pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "Checkout stage completed"
            }
        }

        stage('Build') {
            steps {
                echo "Build stage started"
                bat 'echo Building project...'
            }
        }

        stage('Test') {
            steps {
                echo "Test stage started"
                bat 'echo Running tests...'
            }
        }
    }
}
