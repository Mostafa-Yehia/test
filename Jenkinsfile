pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh "chmod +x test.sh"
                sh "./test.sh"
            }
        }
