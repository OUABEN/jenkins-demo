pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Build en cours...'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Tests en cours...'
            }
        }
        
        stage('Execution Script') {
            steps {
                bat 'test.bat'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Déploiement simulé...'
            }
        }
    }
}