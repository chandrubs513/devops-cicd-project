pipeline {
    agent any

    stages {

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t devops-web:latest .'
            }
        }

        stage('Stop Old Container') {
            steps {
                sh 'docker stop devops-web || true'
                sh 'docker rm devops-web || true'
            }
        }

        stage('Run New Container') {
            steps {
                sh 'docker run -d --name devops-web -p 8090:80 devops-web:latest'
            }
        }

    }
}
