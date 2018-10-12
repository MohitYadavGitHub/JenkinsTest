pipeline {
    agent any
    stages {
        stage('Test') {
            if (env.BRANCH_NAME == 'P3_Dev_CI') {
            steps{
                echo 'I only execute on the master branch'
                }
            } else {
            steps{
                echo 'I execute elsewhere'
                }
            }
        }

        stage('dock'){
            steps{
                sh 'ls'
            }
        }
    }
}
