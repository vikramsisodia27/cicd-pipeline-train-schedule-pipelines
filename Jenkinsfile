pipeline {
  agent any
  stages {
    stage ('Build'){
       steps {
          echo 'Running Build'
          sh './gradlew build --no-daemon'
          archiveArtificats artifacts : 'dist/trainSchedule.zip'
       }
    }
  }
}
