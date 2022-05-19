pipeline {
  agent any {
    stages {
  stage('Download') {
    steps {
      sh 'docker run \'maven:3.3.3\' '
           }
  }
   stage('build') {
    steps {
        sh 'mvn --version'
        sh 'mvn install'
        }
      }
    }
  }
}
