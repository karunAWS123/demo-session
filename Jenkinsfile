pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: 'jenkins', url: 'https://github.com/karunAWS123/sathish.git'
                sh '''ls -l 
git  --version
java --version'''
            }
        }
    }
}
