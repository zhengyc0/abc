pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
        sh 'echo \'build stage\''
        sleep 10
      }
    }
    stage('Test') {
      steps {
        echo 'Test'
        sh 'sh \'ping -c 4 localhost\''
      }
    }
    stage('Deploy') {
      steps {
        sleep 4
      }
    }
  }
}