pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        echo 'hi'
      }
    }

    stage('docker') {
      parallel {
        stage('docker') {
          steps {
            sh '''pwd
ls'''
          }
        }

        stage('dock') {
          steps {
            sh '''date
'''
            sh 'date'
          }
        }

      }
    }

    stage('build') {
      steps {
        echo 'complete'
      }
    }

  }
}