pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello everyone !"'
            }
        }
        stage('Pull') {
            steps {
                sh './jenkins/scripts/pull.sh'
            }
        }
    }
}
