pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        git(url: 'https://github.com/MohitYadavGitHub/JenkinsTest', branch: 'master')
      }
    }
    stage('python') {
      steps {
       sh '/usr/bin/python test.py "hello"'
      }
    }  
     stage('docker-test') {
      agent {
        docker {image 'ubuntu'}
      }
      steps {
       sh 'ls'
      } 
    }
  }
}
