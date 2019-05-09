pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'dir', returnStdout: true)
        bat(script: 'git.exe --version', returnStdout: true, returnStatus: true)
        bat(script: 'C:\\Users\\jian9097\\Documents\\Workspace\\test.bat', returnStatus: true, returnStdout: true)
      }
    }
    stage('Run') {
      steps {
        bat(script: 'node --version', returnStdout: true, returnStatus: true)
      }
    }
  }
}