pipeline {
    agent any
    stages {
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
