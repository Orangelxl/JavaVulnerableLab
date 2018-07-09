pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'building'
      }
    }
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'test'
          }
        }
        stage('daishen') {
          steps {
            echo 'daishen'
          }
        }
      }
    }
  }
}