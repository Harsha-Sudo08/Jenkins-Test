pipeline {
    agent { docker { image 'rust:1.92.0' } }
    stages {
        stage('build') {
            steps {
                sh '
                    echo "building the RUST projects"
                '
            }
        }
        stage('run') {
            steps {
                sh 'echo "RUN THE APPLICATION"'
            }
        }
    }
}