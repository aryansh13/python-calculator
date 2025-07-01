pipeline {
    agent any

    stages {
            stage('Checkout') {
        steps {
            git branch: 'main', url: 'https://github.com/aryansh13/python-calculator.git'
        }
    }

        stage('Test') {
            steps {
                bat 'python3 -m unittest test_calculator.py'
            }
        }
    }
}