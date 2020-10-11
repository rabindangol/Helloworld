pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        echo "This is the build $BUILD_NUMBER of demo $DEMO"
      }
    }

  }
  environment {
    DEMO = '1'
  }
}
