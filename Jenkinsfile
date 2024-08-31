pipeline {
    agent {
        label 'AGENT-1'
    }
    options {
        timeout(time: 5, units: 'SECONDS')
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo This is Build stage'
            }
        }
        stage('Test') {
            steps {
                sh 'echo This is Test stage'
                sh 'sleep 10'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo This is Deploy stage'
            }
        }
    }
}