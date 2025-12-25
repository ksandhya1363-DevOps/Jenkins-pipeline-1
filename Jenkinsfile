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
        stage('MavenSecondStae'){
            tools{
                maven 'Maven_3.9.12'
            }
            steps{
                echo "Hello from second stage"
                sh "mvn -version"
            }
        }

    }
}
