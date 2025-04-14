// Jenkins pipeline
pipeline {
    agent any
    stages {
        stage('Clone Code') {
            steps {
                checkout scm
            }
        }

        stage('Installing Required Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Running App Locally') {
            steps {
                sh 'node app.js'
            }
        }
    }
}
