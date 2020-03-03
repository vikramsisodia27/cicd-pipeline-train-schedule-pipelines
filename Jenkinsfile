pipeline {
  agent only
  stage {
    stage ('Build'){
      echo 'Running Build'
      sh './gradlew build --no-daemon'
      archiveArtificats artifacts : 'dist/trainSchedule.zip'
    }
  }
}
