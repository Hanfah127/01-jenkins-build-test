
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
                echo 'TEST PASSED'
            }
        }
    }
}
