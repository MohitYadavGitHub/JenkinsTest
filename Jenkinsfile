pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        git(url: 'https://github.com/MohitYadavGitHub/JenkinsTest', branch: 'master')
      }
    stage('Test') {
      steps {
        sh 'python test.py test'
      }
    }  
  }
}
