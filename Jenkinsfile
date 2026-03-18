pipeline {
    agent any

    triggers {
        githubPush()
    }

    options {
        skipDefaultCheckout(true)
    }

    stages {
        stage('Clean workspace') {
            steps {
                deleteDir()  // wipes out everything in the workspace
            }
        }
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