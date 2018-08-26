pipeline {
  agent {
    docker {
      image 'myjekins_v0'
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
