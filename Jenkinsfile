/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'node:16-alpine' } }
    stages {
        stage('test') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}

