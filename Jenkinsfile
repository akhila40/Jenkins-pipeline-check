pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "Iam building the image in the docker" '
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Iam Testing the image in the docker" '
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Iam Deploying the image in the Kubernets" '
            }
        }
    }
}
