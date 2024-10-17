pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pwd 
ls
date'''
      }
    }

    stage('test') {
      steps {
        sleep 20
      }
    }

    stage('test3') {
      steps {
        sh 'echo "rmsms"'
      }
    }

  }
}