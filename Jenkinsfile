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
                bat '"C:\\Users\\LENOVO\\AppData\\Local\\Programs\\Python\\Python310\\python.exe" -m unittest test_calculator.py'
            }
        }
    }
}
