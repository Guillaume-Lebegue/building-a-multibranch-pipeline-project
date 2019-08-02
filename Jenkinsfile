pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
            }
        }
        stage('Pull') {
            steps {
                sh './jenkins/scripts/pull.sh'
            }
        }
    }
}
