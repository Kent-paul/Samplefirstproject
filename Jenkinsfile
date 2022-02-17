pipeline {
    agent any
    parameters { 
        choice(name: 'ENV', choices: ['dev', 'test', 'prod'], description: '') 
    }
    stages {
        stage('Buildz') {
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
                echo "environment is in ${params.ENV}"
            }
        }
    }
}
