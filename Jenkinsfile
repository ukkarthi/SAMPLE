pipeline {
  agent any

  stages {
    stage('build') {
      when {
        expression {
          “foo” == “bar”
        }
      }
      steps {
        println('Hello World')
        echo 'Building'
      }
    }

    stage('deploy') {
      steps {
        println("this is the deployment step")
      }
    }

    stage('test') {
      when {
        environment name: ‘JOB_NAME’, value: ‘foo’
      }
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
