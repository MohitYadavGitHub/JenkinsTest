pipeline {
    agent any
    stages {
        stage('Test') {
            if (env.BRANCH_NAME == "P3_Dev_CI") {
                steps {
                    sh 'printenv'
                    
                }
            } else {
            steps {
                 sh 'echo $BRANCH_NAME'
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
