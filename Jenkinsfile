pipeline {
  agent any
  
  stages {
    stage ('build') {
      steps {
        sh 'echo Compile'
      }
    }
    
    stage ('test') {
      steps ('test') {
        sh 'echo Test'
      }
    }
    
    stage ('deploy') {
      steps {
        sh 'echo Deploy'
      }
    }
  }
}
