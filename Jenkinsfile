pipeline {

  agent any

  options {

    buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5')

  }

  stages {

    stage('stage-1') {

      steps {

        sh '''
      echo "This is testbranch2 jenkinsfile"

        '''

      }
    }
      stage('stage-2') {

      steps {

        sh '''
        echo "This is stage 2"
        '''
            }
        }
    }
}
