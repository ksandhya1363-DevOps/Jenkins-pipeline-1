pipeline{
    agent any
    stages{
        stage('Build'){
                steps{
                    echo " *** Building the application *** "
                }
            }
        stage('Tests'){
                    steps{
                        echo "*** Testing the application ***"
                    }
                }
        stage('DeployToDev'){
                    steps{
                        echo " *** Deploying to dev environment ***"
                    }
                }
        stage('DeployToTest'){
                    steps{
                        echo " *** Deploying to Test environment ***"
                    }
                }
        stage('DeployToStage'){
                    steps{
                        echo " *** Deploying to Stage environment ***"
                    }
                }
        stage('DeployToProd'){
                    steps{
                        timeout (time: 10, unit: 'SECONDS')
                        {
                            echo " *** Deploying to Production environment ***"
                            sleep 11
                        }
                    }
                }
        }
    }
