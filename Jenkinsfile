pipeline {
  agent any
  tools {nodejs "node"}
  stages {
    stage('Build') {
      steps {
        sh 'docker-compose -f docker-compose-local.yml up -d'
      }}}}
