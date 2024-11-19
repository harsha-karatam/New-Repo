pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main',
                    credentialsId: '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',
                    url: 'https://github.com/harsha-karatam/New-Repo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build commands here
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deployment commands here
            }
        }
    }
}
