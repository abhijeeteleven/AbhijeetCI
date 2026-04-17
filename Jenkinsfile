pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Install & Test') {
            steps {
                bat 'pip install -r requirements.txt'
                bat 'pytest'
            }
        }
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
