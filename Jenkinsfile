pipeline {
    agent any

    stages {
        stage('Test Git') {
            steps {
                // Kör git-version för att verifiera Jenkins ser Git
                bat 'git --version'
            }
        }

        stage('Test Python') {
            steps {
                // Kör python-version för att verifiera Python är i PATH
                bat 'python --version'
            }
        }

        stage('Build') {
            steps {
                // Exempelsteg, här kan du lägga in dina build-kommandon
                bat 'echo Build step ran successfully!'
            }
        }
    }
}
