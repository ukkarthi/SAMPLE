pipeline {
  agent any

  stages {
    stage('build') {
      parallel {
        stage('Chrome') {
          steps {
            println "RAMA KRISHNA GOVINDA"
            echo "Chrome Tests"
          }
        }
        stage('Firefox') {
          steps {
            println "RADHEY SHYAM"
            echo "Firefox tests"
          }
        }
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
          stage('Internet Explorer') {
            steps {
              println "RAMA SITA GOVINDA"
              echo "IE tests"
            }
          }
        }
      }
    }
}
