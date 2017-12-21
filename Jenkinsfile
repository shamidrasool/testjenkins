pipeline {
  agent { any }
  stages {
    stage ('build') {
      steps {
        sh 'python3 -V'
        echo 'Running test script'
        sh 'testscript.py'
      }
    }
  }
    
}
    
