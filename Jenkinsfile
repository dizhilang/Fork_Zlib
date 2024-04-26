pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        bat(script: 'echobat', encoding: 'echo "hello world"', label: 'hello world', returnStatus: true, returnStdout: true)
      }
    }

  }
}