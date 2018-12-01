pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'build'
          }
        }
        stage('test') {
          steps {
            sh '/bin/sh /d/jenkins_installed/sample.sh'
          }
        }
      }
    }
  }
}