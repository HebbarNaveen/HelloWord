pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        dotnetRestore(project: '**/*.csproj')
        dotnetClean()
        dotnetBuild(noRestore: true, project: '**/*.csproj', configuration: 'Release')
      }
    }

  }
}