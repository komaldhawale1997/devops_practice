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
                changeset "file.txt"
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
