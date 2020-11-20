pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        echo '1'
      }
    }

    stage('2') {
      steps {
        echo '22'
        sh '''echo "Hello1"
echo "Hello2"
echo "Hello3"
echo "Hello4"
echo "Hello5"'''
      }
    }

    stage('3') {
      steps {
        echo '333'
      }
    }

  }
}