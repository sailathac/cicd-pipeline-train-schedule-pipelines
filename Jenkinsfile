pipeline {
  agent any
  stages {
    stage ('Build') {
      echo "Running Build Automtion"
      sh "./gradlew build --no-daemon"
      archiveArtifacts: "dist/trainSchedule.zip"
    }
  }
}
