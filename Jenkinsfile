pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
        sh 'sh \'ping -c 2 localhost\''
      }
    }
    stage('Test') {
      steps {
        echo 'Test'
      }
    }
    stage('Deploy') {
      steps {
        sleep 4
      }
    }
  }
}