pipeline{
    agent any
    stages{
    stage('Build') {
    steps {
                bat 'dotnet build %WORKSPACE%\\ServerApp.sln /p:PublishProfile=" %WORKSPACE%\\ServerApp\\Properties\\PublishProfiles\\FolderProfile.pubxml" /p:Platform="Any CPU" /p:DeployOnBuild=true /m'
            }
    }
    }
}