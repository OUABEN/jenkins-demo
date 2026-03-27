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
                // Afficher le répertoire de travail
                bat 'echo Current directory: %CD%'
                
                // Lister les fichiers
                bat 'dir'
                
                // Vérifier si test.bat existe
                bat 'if exist test.bat (echo test.bat found) else (echo test.bat NOT found)'
                
                // Exécuter le script
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