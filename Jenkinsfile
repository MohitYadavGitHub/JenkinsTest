pipeline {
  agent {
    docker {
      image 'hello-world'
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
