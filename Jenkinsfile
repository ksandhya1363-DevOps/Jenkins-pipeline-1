pipeline{
    agent any
    tools {
        maven 'Maven_3.8.9'
    }
    stages{
        stage('Maven'){
            steps{
                echo "Hello this is Maven version"
                sh "mvn -version"
            }
        }

    }
}
