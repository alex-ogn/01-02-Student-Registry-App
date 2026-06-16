pipeline{
    agent any

    stages{
        stage("Install Dependecies") {
            steps{
                bat 'npm install'
            }
        }
        stage("Test") {
            steps{
                bat 'npm test'
            }
        }
    }
}