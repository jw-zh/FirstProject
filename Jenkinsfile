pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'dir', returnStdout: true)
      }
    }
    stage('Run') {
      steps {
        bat(script: 'node -version', returnStdout: true, returnStatus: true)
      }
    }
  }
}