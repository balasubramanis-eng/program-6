pipeline {
    agent any

    stages {

        stage('Run Unit Test') {
            steps {
                sh 'python -m unittest test_app.py'
            }
        }

    }
}
