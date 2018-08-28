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
        bat 'dir'
      }
    }  
  }
}
