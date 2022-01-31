pipeline {
  agent any 
  stages {
    stage('Build') {
      steps {
       sh 'echo "code from github!!" '
        sh '''
        echo " multiline comment also run "
        ls -lah
        '''
      }
    }
  }
}
