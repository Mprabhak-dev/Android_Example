pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh './gradlew clean assembleDebug test connectedAndroidTest assembleRelease'
      }
    }

  }
}