pipeline {
    agent any
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