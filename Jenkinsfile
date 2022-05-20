pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        dotnetRestore()
        dotnetClean()
        dotnetBuild(noRestore: true, configuration: 'Release')
      }
    }

  }
}