pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                withDotNet()
                dotnetBuild()
            }
        }
    }
}