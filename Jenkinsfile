pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo "Welcome to jenkins Pipeline "
                error "This is a failure"
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
