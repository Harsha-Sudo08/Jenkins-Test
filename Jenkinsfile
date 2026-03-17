pipeline {
    agent { docker { image 'rust:1.92.0' } }
    stages {
        stage('build') {
            steps {
                sh 'rustc --version'
            }
        }
    }
}