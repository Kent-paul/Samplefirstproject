pipeline {
    agent any
    parameters { 
        choice(name: 'ENV_CHOICE', choices: ['dev', 'test', 'prod'], description: '') 
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
                echo "environment is in" $ENV_CHOICE
            }
        }
    }
}
