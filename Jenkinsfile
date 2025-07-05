pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo 'Code is already checked out by Jenkins from GitHub!'
            }
        }
        stage('Build') {
            steps {
                sh 'chmod +x test_script.sh'
                sh './test_script.sh'
            }
        }
    }
}
