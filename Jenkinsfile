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
                echo "building"
            }
        }

        stage('Run') {
            steps {
                echo "running"
            }
        }
    }
}