pipeline {
  agent {
    node {
      label 'slave1'
    }

  }
  stages {
    stage('') {
      steps {
        sh '''echo " This is my first project"
date
curl www.google.com > sample.txt
grep "google" sample.txt
'''
      }
    }

  }
}