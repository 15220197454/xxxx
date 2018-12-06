pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'echo 1111'
      }
    }
    stage('') {
      steps {
        sleep(time: 4, unit: 'SECONDS')
      }
    }
    stage('test1') {
      steps {
        echo 'test'
      }
    }
  }
}