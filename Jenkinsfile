pipeline {
  agent any
  stages {
    stage('deploy') {
      agent any
      steps {
        sshCommand(failOnError: true, command: 'mkdir testcai')
      }
    }

  }
}