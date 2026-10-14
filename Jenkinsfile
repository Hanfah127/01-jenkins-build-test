
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building my application'
                bat 'type app.txt'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing my application'
                bat 'if exist app.txt (echo TEST PASSED) else (exit /b 1)'
            }
        }
    }
}
