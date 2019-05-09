pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'npm -version', returnStdout: true)
      }
    }
    stage('Run') {
      steps {
        bat(script: 'python test.py', returnStdout: true, returnStatus: true)
      }
    }
  }
}