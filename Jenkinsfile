pipeline {
    agent {
        docker {
            image 'dotnet:6.0-alpine'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'dotnet --version'
                sh 'dotnet build'
            }
        }
    }
}