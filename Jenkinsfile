pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello everyone i'm Gav!"'
            }
        }
        stage('Pull') {
            steps {
                sh './jenkins/scripts/pull.sh'
            }
        }
    }
}
