pipeline{
    agent{
        label 'java-slave'
    }
    stages{
        stage ('hostname'){
            steps {
                sh 'hostname -i'
            }
        }
    }
}
