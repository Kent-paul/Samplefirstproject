pipeline {
    agent any
    parameters { 
        choice(name: 'ENV', choices: ['dev', 'test', 'prod'], description: '') 
    }
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
                echo "params.ENV"
            }
        }
    }
}
