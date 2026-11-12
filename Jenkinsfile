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
}// trigger build 2026-11-12T12:06:22+05:30
// trigger2 2026-11-12T12:09:55+05:30
// trigger3 2026-11-12T12:14:52+05:30
// trigger4 2026-11-12T12:18:22+05:30
// trigger5 2026-11-12T12:20:41+05:30
// trigger6 2026-11-12T12:22:54+05:30
