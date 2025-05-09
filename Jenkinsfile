pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/your-username/my-simple-app.git'
            }
        }

        stage('Build') {
            steps {
                echo 'No build needed for HTML...'
            }
        }

        stage('Test') {
            steps {
                echo 'No tests, just a static file...'
            }
        }

        stage('Deploy') {
            steps {
                sh './deploy.sh'
            }
        }
    }
}
