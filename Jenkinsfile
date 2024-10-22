pipeline {
    agent { docker 'python:3.5.1' }
    stages {
        stage('build') {
            steps {
                sh 'python test-0.py'
                sh 'python --version'
            }
        }
    }
}