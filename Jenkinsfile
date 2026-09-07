pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/pranayaparthiban/Q2_Python_Calculator.git'
            }
        }

        stage('Build') {
            steps {
                bat 'python calculator.py'
            }
        }
    }
}