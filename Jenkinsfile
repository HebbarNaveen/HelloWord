pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        dotnetRestore(source: 'HelloWord.sln')
        dotnetClean()
        dotnetBuild(noRestore: true, configuration: 'Release')
      }
    }

  }
}