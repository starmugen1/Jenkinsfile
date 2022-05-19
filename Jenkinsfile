pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
          sh 'mvn --version'
          sh 'mvn install'
       }
    stage('Deployment') {
      steps {
          echo "Now Deploying"
    }
  }
}
