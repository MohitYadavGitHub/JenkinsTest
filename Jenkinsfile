pipeline {
    agent any
    stages {
        stage('Test') {
            when {branch 'P3_Dev_CI'}
            steps {
                sh 'printenv'
                
            }
        }

        stage('dock'){
            steps{
                sh 'ls'
            }
        }
    }
}
