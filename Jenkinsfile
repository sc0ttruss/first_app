pipeline {
  agent {
    docker {
      image 'jenkins'
      args '-p 8081:8080'
    }
    
  }
  stages {
    stage('') {
      steps {
        emailext(subject: 'starting build', body: 'lets get started', attachLog: true, compressLog: true, to: 'scott.russell@inetmedia.co.uk')
      }
    }
  }
}