pipeline {
    agent {
        docker login,
        docker { image 'php' }
    }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}