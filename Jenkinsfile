pipeline {
  agent any

  stages {
    stage('build') {
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
      steps {
        println ("This is the test step")
      }
    }

    stage('UAT') {
      steps {
        println("UAT is being performed")
      }
    }

    stage('Browser Tests') {
      parallel {
        stage('Chrome') {
          steps {
            echo "Chrome Tests"
          }
        }
        stage('Firefox') {
          steps {
            echo "Firefox tests"
          }
        }
        stage('Internet Explorer') {
          steps {
            echo "IE tests"
          }
        }
      }
    }
  }
}
