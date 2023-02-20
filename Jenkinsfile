pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat "node hello.js"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
    }
}