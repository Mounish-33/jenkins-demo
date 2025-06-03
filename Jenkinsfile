pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/Mounish-33/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'javac Main.java'
            }
        }

        stage('Test') {
            steps {
                sh 'java Main'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
