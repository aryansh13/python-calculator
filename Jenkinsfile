pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/aryansh13/python-calculator.git'
            }
        }

        stage('Test') {
            steps {
                sh 'python3 -m unittest test_calculator.py'
            }
        }
    }
}
