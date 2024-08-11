pipeline {
    agent any  
    stages {
        stage('Checkout') {
            steps {
                // Checkout code from the repository
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
                // Example build step
                sh 'echo Building the project...'
            }
        }
