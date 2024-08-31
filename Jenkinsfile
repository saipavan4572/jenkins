pipeline {
    agent {
        label 'AGENT-1'
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
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo This is Deploy stage'
            }
        }
    }
}