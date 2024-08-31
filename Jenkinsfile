pipeline {
    agent {
        label 'AGENT-1'
    }
    options {
        //timeout(time: 5, unit: 'SECONDS')
        timeout(time: 30, unit: 'MINUTES')
        disableConcurrentBuilds()  // it will not allow concurrent builds
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