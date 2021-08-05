pipeline {
  agent any
  stages {
    stage('build') {
      agent any
      steps {
        echo 'hello roopa'
      }
    }

    stage('test') {
      steps {
        sh 'javac helloworld1.java'
      }
    }

  }
}
