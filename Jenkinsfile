pipeline {
  agent {
    docker {
      image 'myhello'
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
