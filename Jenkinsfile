pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Build') {
            steps {
                echo 'Running build...'
                // Add build commands here, like:
                // sh 'make build'
                // sh 'docker build -t my-app .'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // sh 'npm test' or your test command
            }
        }
    }
}
