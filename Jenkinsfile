pipeline {
    agent { docker 'node:10.15.3' }
    stages {
        stage('Install') {
            steps {
                sh 'npm install'
            }
        }
        stage('Build') {
            steps {
                sh 'npm run build:prod'
            }
        }
    }
}