pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'building the application...'
            }
        }
        stage('Test') {
            steps {
                echo 'testing the application...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploying the application...'
                echo "environment is in 3 ${params.ENV}"
            }
        }
    }
}
