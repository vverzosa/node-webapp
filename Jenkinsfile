pipeline {
  agent {
    label 'linux-node'
  }
  
  stages {
    stage("Build") {
      steps {
        script {
          docker.build('node-webapp').run('-p 3000:3000') 
        }
      }
    }
  }
{
