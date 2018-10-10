pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'printenv'
                sh 'echo $env.BRANCH_NAME'
            }
        }
        stage('dock'){
            steps{
                sh 'ls'
            }
        }
    }
}
