pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        sh 'npm install'
      }
    }

    stage('Update') {
      steps {
        sh 'apt update && apt install yarn -y'
      }
    }

  }
}