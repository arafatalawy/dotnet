pipeline
{

    agent any
    stage("Building")
    {

    steps{
        sh "docker build -t dotnet"
    }
    stage("Running")
    {
     sh "docker run --rm dotnet"

    }
    }
}
