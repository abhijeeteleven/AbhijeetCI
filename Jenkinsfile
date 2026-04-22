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
                bat 'python test_sample1.py'
                bat 'pytest'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }

    }
}
