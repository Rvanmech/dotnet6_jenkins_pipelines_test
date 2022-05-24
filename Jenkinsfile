pipeline {
    agent { label 'dotnet-6' }
    stages {
        stage('build') {
            steps {
                dotnet build
            }
        }
    }
}