pipeline {
    agent any
    stages {
        
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/AJLong99/Test'
          }
        }
        stage('Build') {
            steps {
                sh 'echo "Building the App"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying the app"'
            }
        }
    }
}
