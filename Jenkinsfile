pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        sh 'python3 -V'
        echo 'Running test script'
        sh 'chmod +x testscript.py'
        sh './testscript.py'
      }
    }
  }
    
}
    
