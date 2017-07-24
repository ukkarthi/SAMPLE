pipeline {
  agent any

  stages {
    stage('build') {
      steps {
        println('Hello World')
      }
    }

    stage('deploy') {
      steps {
        mkdir "C:\Tools\SSS"
      }
    }

    stage('test') {
      steps {
        println ("This is the test step")
      }
    }

    stage('UAT') {
      steps {
        println("UAT is being performed")
      }
    }
  }
}
