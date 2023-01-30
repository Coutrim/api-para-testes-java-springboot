pipeline{
    agent any

    stages{
        stage('Build image'){
            steps{
                script{
                    dockerapp = docker.build("henriquecoutrim/api-java-springboot", '-f ./src/Dockerfile ./src')
                }
            }
        }
    }
}