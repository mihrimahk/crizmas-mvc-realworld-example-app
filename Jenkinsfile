pipeline {
    agent any

    stages {
        
        stage('checkout codes ') {
            steps {
        git 'https://github.com/mihrimahk/crizmas-mvc-realworld-example-app'

            }
        }
        stage('build docker') {
            steps {
                echo 'building docker'
                sh 'docker build -t test-pipeline .'
            }
        }
    }
}
