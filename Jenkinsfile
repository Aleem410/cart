@Library('roboshop')
pipeline {
  agent any
  stages {
    stage('code quality'){
      steps {
        script {
          log.info 'code quality'
     }
    }
  }

    stage('Test cases'){
      steps {
         echo 'Test cases'
        }
      }

    stage('Publish release'){
      steps {
         echo 'Publish release'
       }
    }
  }
}