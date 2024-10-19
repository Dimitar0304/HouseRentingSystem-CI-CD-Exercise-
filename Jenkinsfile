pipeline{
    agent any
    stages{
        stage('Restore NuGet packages'){
            steps{

              bat 'dotnet restore'
            }
        }
    }
}