pipeline {
  agent any
  stages {
    stage("build") {
      steps {
        sh """
          docker build -t dotnet .
          dotnet --list-sdks
        """
      }
    }

  }
}
