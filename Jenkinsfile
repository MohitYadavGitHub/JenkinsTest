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
        bat 'C:\\Users\\mohit\\AppData\\Local\\Programs\\Python\\Python36\\python.exe test.py "hello"'
      }
    }  
  }
}
