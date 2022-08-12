pipeline {
  agent {
        docker {
            image 'node:6-alpine'
            args '-p 3000:3000'
        }
    }
  tools {nodejs "node"}
  stages {
    stage('Build') {
      steps {
        sh 'sudo apt install nodejs'
        sh 'sudo apt install npm'
      }}}}
