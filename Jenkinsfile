/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.10.7-alpine' } }
    stages {
        stage('Build') {
            steps {
                sh 'python --version'
                sh 'echo "Hell World"'
                sh '''
                    echo "Multiline what?"
                    ls -lah
                '''
            }
        }
    }
}
