pipeline{
    environment{
        course="Kubernetes"
        name="siva"
        cloud ="Azure"
    }
    stages{
        stage('FirstStage'){
                environment{
                    cloud="GCP"
                }
                steps{
                    echo "**** Building the application in first stage"
                    echo "**** Welcome ${name} ****"
                    echo "**** You are enrolled to ${course}, All the best ${name}****"
                    echo "**** You are certified in ${cloud} cloud ****"
                 }
        }
        stage('SecondStage'){
            environment{
                    name="Sandhya"
                    course="Azure DevOps"
            }
            steps{
                echo "**** Building the application in the second stage"
                echo "**** Welcome ${name} ****"
                echo "**** You are enrolled to ${course}, All the best ${name} ****"
                echo "**** You are certified in ${cloud}****"
            }
        }
    }
}
