pipeline{
    agent any

    environment{
        course = "kubernetes"
        GITHUB_CREDS = credentials('slave_john_credentials')
    }
    stages{
        stage('Build'){
            steps{
            echo "*** My Github credentials are ${GITHUB_CREDS}***"
            echo "*** My Username is: ${GITHUB_CREDS_USR}***"
            echo "*** My Password is: ${GTHUB_CREDS_PSW}***"

            }
        }
    }
}
