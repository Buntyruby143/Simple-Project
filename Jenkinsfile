pipeline {
  agent {
    node {
      label 'slave1'
    }

  }
  stages {
    stage('Display Message') {
      parallel {
        stage('Display Message') {
          steps {
            sh '''echo " This is my first project"
            sh 'date'
            sh  'curl www.google.com > sample.txt'
            sh   'grep "google" sample.txt'
'''
            error 'There is a error in this step'
          }
        }

        stage('Current date and time') {
          steps {
            sh '''echo " Todays date and current time"
date'''
          }
        }

      }
    }

  }
}
