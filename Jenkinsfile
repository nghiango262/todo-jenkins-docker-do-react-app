pipeline {
    agent none 

    stages {
        stage('Example stage 1') {
            environment {
                BITBUCKET_COMMON_CREDS = credentials('jenkins-bitbucket-common-creds')
            }
            steps {
                echo 'Cai quan 1'
            }
        }
        stage('Example stage 2') {
            steps {
                echo 'Cai quan 2'
            }
        }
    }
}
