pipeline {
  agent {
    docker {
      image 'localhost:5000/myjim'
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
