pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO tyrone"'
      sh '''
        echo "Welcome to B2"
        uname
        '''
      }
    }
    stage ('Test') {
      steps {
      sh 'echo "HELLO sanderson"'
      sh '''
        echo "This is testing"
        pwd
        '''
      }
    }
  }
} 
