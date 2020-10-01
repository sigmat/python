pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'echo "build..."'
            }
        }
        
        stage('staging') {
            steps {
                sh 'python --version'
                sh 'echo "staging..."'
            }
        }

        stage('QA') {
            steps {
                sh 'python --version'
                sh 'echo "QA..."'
            }
        }

    }
}
