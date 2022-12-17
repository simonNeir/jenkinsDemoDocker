pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'This is the build stage'
        node('Node_19.2') {
        node('Node19.2') {
          sh 'npm init -y'
          sh 'npm i'
        }
      }
    }
    stage('Test') {
      steps {
        echo 'This is the test stage'
      }
    }
    stage('Deploy') {
      steps {
        echo 'This is the deploy stage'
      }
    }
  }
}
