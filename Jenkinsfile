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
        bat 'npm install'
      }}}}