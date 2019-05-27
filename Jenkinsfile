pipeline {
  agent { node { label 'maven' } }
  stages {
    stage('clean') {
      steps {
        sh "mvn clean"
      }
    }
  }
}