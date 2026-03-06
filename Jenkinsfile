pipeline {
    agent {
        node {
            label 'nodejs'
        }
    }
    stages {
        stage('Backend Tests') {
            step {
                sh 'node ./backend/test.js'
            }
        }
        stage('Frontend Test') {
            step {
                sh 'node ./frontend/test.js'
            }
        }
    }
}