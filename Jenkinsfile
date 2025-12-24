pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                retry(3){
                         echo "Welcome to jenkins Pipeline "
                error "This is a failure"
                }
                echo "After 3 retries"
               
            }
        }
        stage('Scans'){
            steps{
                echo "Executing sonar scans"
            }
        }
        stage('Maven'){
            steps{
                echo "Build Maven"
            }
        }
    }
}
