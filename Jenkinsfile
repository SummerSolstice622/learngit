pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        git(url: 'https://tfs-glo-lexisadvance.visualstudio.com/DefaultCollection/TestAutomation/_git/LA.APAC.TestAutomation', branch: 'dev')
      }
    }
  }
}