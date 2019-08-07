pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/Guillaume-Lebegue/building-a-multibranch-pipeline-project.git', branch: 'master', changelog: true, poll: true)
        sh jenkins/scripts/SMG.sh
      }
    }
  }
}