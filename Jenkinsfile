pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                sh '''
                echo "Building Rust project..."
                cargo build --release
                '''
            }
        }

        stage('Run') {
            steps {
                sh '''
                echo "Running application..."
                ./target/release/your_binary_name
                '''
            }
        }
    }
}