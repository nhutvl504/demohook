pipeline {
    agent none
    stages {
       
        stage('Deploy React App') {
            agent { label 'nodejs-slave-5b4179b5' }
            steps {
                echo 'Starting React.js app...'
                sh 'node --version'
                echo 'Long hhi'
            }
        }
        stage('Build Java Project') {
            agent { label 'java-slave-cbbf8394' }
            steps {
                echo 'Building Java project...'
                sh 'java --version'
            }
        }
    }
}
