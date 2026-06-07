pipeline{
    agent any
    stages{
        stage('Checkout'){
            steps{
                echo 'downloading source code'
            }
        }
        stage('Docker Build'){
            steps{
                bat 'docker build -t myapp:latest .'
            }
        }
    }
}
