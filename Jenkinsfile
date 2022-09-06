pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
          withmaven{
            sh 'mvn clean install'
          }
      }
    }

  }
}
