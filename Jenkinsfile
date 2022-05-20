pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        dotnetRestore()
        echo '\'${env.WORKSPACE}\''
      }
    }

  }
}