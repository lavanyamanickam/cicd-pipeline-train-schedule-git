pipeline {
  agent any
    stages {
      stage ('Build') {
        echo "Running the automated tests"
        sh './gradlew build --no-daemon'
        archiveArtifacts artifact 'dist/trainSchedule'
        }
      }
    }
