pipeline {
    agent { docker { image 'php:7.3' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
