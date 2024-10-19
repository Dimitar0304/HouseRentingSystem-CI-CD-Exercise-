pipeline{
    agent any
    stages{
        stage('Restore NuGet packages'){
            steps{

              bat 'dotnet restore'
            }
        }
        stage('build app')
        {
            steps{
                bat 'dotnet build'
            }
        }
        stage ('Run test'){
            steps{
                bat 'dotnet test'
            }
        }
    }
}