pipeline {
  agent {
    docker {
      args '-p 8081:8080'
      image 'ubuntu'
    }
    
  }
  stages {
    stage('error') {
      steps {
        emailext(subject: 'starting build', body: 'lets get started', attachLog: true, compressLog: true, to: 'scott.russell@inetmedia.co.uk')
      }
    }
  }
}