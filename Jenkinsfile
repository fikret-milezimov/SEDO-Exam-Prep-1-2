pipeline {
    agent any

    stages {
        stage('Dotnet Restore') {
          
                

            steps {
                bat 'dotnet restore'
            }
        }
        stage('Dotnet build') {
          
                

            steps {
                bat 'dotnet build --no-restore'
            }
        }
        stage('Dotnet test') {
           
                

            steps {
                bat 'dotnet test --no-build --verbosity normal'
            }
        }
        
             
    }
}