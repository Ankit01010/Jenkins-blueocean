pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
date

'''
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'teststep'
          }
        }

        stage('tast par') {
          steps {
            echo 'test par'
          }
        }

      }
    }

    stage('deplot') {
      steps {
        echo 'print message'
        sleep 13
      }
    }

  }
}