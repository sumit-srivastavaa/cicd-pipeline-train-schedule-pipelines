jenkins all source:

https://github.com/linuxacademy/cicd-pipeline-train-schedule-pipelines

pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: dist/trainSchedule.zip
      }
    }
  }
}
