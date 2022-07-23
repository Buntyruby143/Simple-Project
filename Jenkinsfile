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
date

'''
          }
        }

        stage('Create files and Directories') {
          steps {
            sh '''echo "Creating python and ruby files"

touch python.txt ruby.txt

echo "create a folder"

mkdir pgm

echo "list out the files and directories"

ls -lrth '''
          }
        }

      }
    }

  }
}