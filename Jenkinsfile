pipeline{
    agent any
   /* agent{
        label 'java-slave'
    }*/
    stages{
        stage ('hostname'){
            steps {
                sh 'hostname -i'
            }
        }
        stage('first-stage'){
            steps{
                echo "Hi this is vs code"
            }
        }
    }
}
