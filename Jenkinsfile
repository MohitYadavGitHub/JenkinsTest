pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'docker ps'
            }
        }
        stage('dock'){
            agent{
                docker {image : 'ubuntu'}
            }
            steps{
                sh 'ls'
            }
        }
    }
}
