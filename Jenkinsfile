pipeline {
    agent any

    stages {

        stage('Install Dependencies') {
            steps {
                bat '"C:\\Users\\Inbarasanvk\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" -m pip install -r CodeAlpha_CreditScoring/requirements.txt'
            }
        }

        stage('Run Project') {
            steps {
                bat '"C:\\Users\\Inbarasanvk\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" CodeAlpha_CreditScoring/main.py'
            }
        }

    }
}
