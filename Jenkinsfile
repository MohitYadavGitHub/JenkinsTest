pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        git(url: 'https://github.com/MohitYadavGitHub/JenkinsTest', branch: 'master')
      }
      steps {
        bat '/usr/bin/python test.py "hello"'
      }
    }    
}
