pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Checking out code...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Nothing to build for HTML!'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Copying HTML to deployment directory...'
                sh 'mkdir -p /var/www/html/simple-site'
                sh 'cp index.html /var/www/html/simple-site/index.html'
            }
        }
    }
}
