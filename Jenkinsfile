pipeline {
    agent any

    stages {

        stage('Install Dependencies') {
            steps {
                bat 'python -m pip install -r CodeAlpha_CreditScoring/requirements.txt'
            }
        }

        stage('Run Project') {
            steps {
                bat 'python CodeAlpha_CreditScoring/main.py'
            }
        }

    }
}
