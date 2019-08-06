pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/Guillaume-Lebegue/building-a-multibranch-pipeline-project.git', branch: 'master', poll: true, changelog: true)
        sh 'echo "i\'m Dav"'
      }
    }
  }
}