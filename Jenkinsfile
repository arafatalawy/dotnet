pipeline
{

    agent any
    stages
    {
    stage("Building")
    {

    steps{
        sh "docker build -t dotnet ."
    }
   
    }
     stage("Running")
    {

     steps{

       
     sh "docker run --rm dotnet"
     }
    }
    }
}
