pipeline {
    agent any

    stages {

        stage('Install Dependencies') {
            steps {
                bat '"C:\\Users\\Inbarasanvk\\AppData\\Local\\Microsoft\\WindowsApps\\python.exe" -m pip install -r CodeAlpha_CreditScoring/requirements.txt'
            }
        }

        stage('Run Project') {
            steps {
                bat '"C:\\Users\\Inbarasanvk\\AppData\\Local\\Microsoft\\WindowsApps\\python.exe" CodeAlpha_CreditScoring/credit_scoring.py'
            }
        }

    }
}
