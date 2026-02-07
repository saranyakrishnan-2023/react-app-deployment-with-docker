pipeline {
    agent any

    stages {
        stage('Build & Push Docker Image') {
            steps {
                sh 'chmod +x build.sh'
                sh './build.sh'
            }
        }
    }
}

