pipeline {
    agent any

    stages {

        stage('Install Dependencies') {
            steps {
                bat '"C:\\Users\\Inbarasan\\AppData\\Local\\Programs\\Python\\Python312\\python.exe" -m pip install -r CodeAlpha_CreditScoring/requirements.txt'
            }
        }

        stage('Run Project') {
            steps {
                bat '"C:\\Users\\Inbarasan\\AppData\\Local\\Programs\\Python\\Python312\\python.exe" CodeAlpha_CreditScoring/credit_scoring.py'
            }
        }

    }
}
