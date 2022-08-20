pipeline {
  agent any
  stages {
    stage ('Build') { 
      steps {
        echo "Building the project with gradle"
        sh './gradlew build'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip
      }
    }
  }
}
