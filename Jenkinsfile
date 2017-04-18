pipeline {
  agent none
  stages {
    stage('First stage') {
      steps {
        node(label: 'dockerslave')
      }
    }
  }
}