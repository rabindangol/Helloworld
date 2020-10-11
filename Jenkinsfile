pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        echo "This is the build $BUILD_NUMBER of demo $DEMO"
        sh 'echo "This is build $BUILD_NUMBER of demp $DEMO v2'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}