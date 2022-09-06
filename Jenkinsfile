pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
          withMaven(globalMavenSettingsConfig: 'null', jdk: 'java11', maven: 'Maven3', mavenSettingsConfig: 'null') {
    // some block
}
      }
    }

  }
}
