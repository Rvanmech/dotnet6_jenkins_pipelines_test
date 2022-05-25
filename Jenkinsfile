pipeline {
    agent { label 'dotnet-6' }
    stages {
        stage('build') {
            steps {
                sh 'dotnet build'
            }
        }
        stage('test') {
            steps {
                sh 'dotnet test'
            }
        }
    }
}
