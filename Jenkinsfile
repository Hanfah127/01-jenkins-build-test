
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building my application'
                sh 'cat app.txt'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing my application'
                sh 'grep -q "My first CI/CD application" app.txt'
                sh 'grep -q "Version 1.0" app.txt'
                echo 'TEST PASSED: Application name and version are correct'
            }
        }
    }
}
