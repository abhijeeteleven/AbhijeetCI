pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code already checked out by Jenkins (SCM)'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
                // Example:
                // bat 'npm install'
                // bat 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example:
                // bat 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Example:
                // bat 'copy files or deploy script'
            }
        }
    }
}
