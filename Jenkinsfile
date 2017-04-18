pipeline {
  agent none
  stages {
    stage('error') {
      steps {
        emailext(subject: 'starting build', body: 'lets get started', attachLog: true, compressLog: true, to: 'scott.russell@inetmedia.co.uk')
      }
    }
  }
}