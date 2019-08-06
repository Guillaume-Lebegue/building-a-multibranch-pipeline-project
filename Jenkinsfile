pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/Guillaume-Lebegue/building-a-multibranch-pipeline-project.git', branch: 'master', credentialsId: 'b11f2a9a-fea9-4849-8753-eace4390c845', poll: true)
        sh 'echo "i\'m Dav"'
      }
    }
  }
}