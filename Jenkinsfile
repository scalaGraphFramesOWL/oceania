pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'job1'
      }
    }
    stage('stage2') {
      steps {
        input(message: 'enter your choice', id: 'userinput')
      }
    }
    stage('stage3') {
      steps {
        echo '$userinput'
      }
    }
  }
}