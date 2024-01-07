pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/AdnanMahmud1/react-resume-adnan.git', branch: 'master')
      }
    }

    stage('Log') {
      parallel {
        stage('Log') {
          steps {
            sh 'ls -la'
          }
        }

        stage('NPM Package Install') {
          steps {
            sh 'npm i --force'
            sh 'npm i'
          }
        }

      }
    }

  }
}