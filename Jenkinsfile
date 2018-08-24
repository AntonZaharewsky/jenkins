pipeline {
    agent {
        docker { login image 'php' }
    }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}