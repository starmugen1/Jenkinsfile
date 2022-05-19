pipeline {
  agent any

  stages {
    stage('Build') {
  steps {
    sh 'mvn --version'
  }
    
  tools {
    maven 'Maven3'
  }
}
    stage('Deployment') {
      steps {
          echo "Now Deploying"
        }
      }
   }
}

