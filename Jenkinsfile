pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'mvn clean'
      }
    }
  }
  environment {
    mvn = '11'
  }
}