pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'b3454d55-f436-4f61-ba1b-ca97095ac0a4', url: 'git@github.com:Kent-paul/Samplefirstproject.git']]])
            }
        }
        stage('Build') {
            steps {
                git checkout ${GIT_BRANCH}
            }
        }
    }
}
