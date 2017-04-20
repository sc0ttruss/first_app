pipeline {
  agent none
  stages {
    stage('First stage') {
      steps {
        node(label: 'jenkins-01')
        sh 'echo `ls -al` '
      }
    }
  }
}