pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh "echo step1"
                sh "chmod +x *.sh"
                sh "./test.sh"
            }
        }
    }
}
