pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Lucifer173-create/jenkins-3.git',
                    credentialsId: 'github-creds'
            }
        }

        stage('Status') {
            steps {
                echo "Repository cloned successfully"
            }
        }
    }
}