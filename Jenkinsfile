pipeline {
  agent {
    docker {
      image 'ubuntu'
      args 'ls'
    }

  }
  stages {
    stage('Test') {
      steps {
        git(url: 'https://github.com/MohitYadavGitHub/JenkinsTest', branch: 'master')
      }
    }
  }
}