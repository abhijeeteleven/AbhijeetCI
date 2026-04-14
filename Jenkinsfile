pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main',
                url: 'https://github.com/your-username/your-repo.git'
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
