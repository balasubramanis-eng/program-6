pipeline {
    agent any

    stages {

        stage('Clone Code') {
            steps {
                git 'https://github.com/balasubramanis-eng/program-6.git'
            }
        }

        stage('Run Unit Test') {
            steps {
                sh 'python -m unittest test_app.py'
            }
        }

    }
}
