pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        dotnetBuild(project: 'HelloWord/.*.csproj')
      }
    }

  }
}