pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'ls -l'
            }
        }
        stage('dock'){
            agent{
                docker {image 'ubuntu'}
            }
            steps{
                sh 'ls'
            }
        }
    }
}
