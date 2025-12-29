pipeline{
    agent{
        label 'java-slave'
    }
    environment{
        DEPLOY_TO = 'development'
    }
    stages{
        stage('ProdEnv'){
            when{
               environment name : 'DEPLOY_TO', value : 'development' 
            }
            steps{
                echo "**** Deploying to Production ****"
            }
        }
    }
}
