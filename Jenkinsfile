pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sshScript(script: '/tmp/test.sh', failOnError: true, remote: 'oelser3.kovaion.com')
      }
    }
  }
}