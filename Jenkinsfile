pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'printenv'
                print $env.BRANCH_NAME
            }
        }
        stage('dock'){
            steps{
                sh 'ls'
            }
        }
    }
}
