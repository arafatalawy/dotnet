pipeline {
  agent any
  stages {
    stage("build") {
      steps {
        sh """
          docker build -t dotnet .
        """
      }
    }
    stage("run") {
      steps {
        sh """
          docker run --rm dotnet
        """
      }
    }
  }
}
