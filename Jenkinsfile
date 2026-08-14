pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application wow'
            }
        }

        stage('Test') {
            when{
                changestate "file.txt"
            }
            steps {
                echo 'Testing application'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}
