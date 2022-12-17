pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'This is the build stage'
        node('node') {
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
