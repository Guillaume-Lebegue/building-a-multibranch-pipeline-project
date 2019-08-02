pipeline {
    agent any
    stages {
        stage('Pull') {
            steps {
                sh './jenkins/scripts/pull.sh'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "i\'m Dav"'
            }
        }
    }
}
