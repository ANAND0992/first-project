pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm  // Checkout the Git repository
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build commands here (e.g., Maven, Gradle, npm)
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test commands here (e.g., unit tests)
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deployment steps (e.g., deploy to server)
            }
        }
    }
}
