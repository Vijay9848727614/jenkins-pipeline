pipeline {
  agent any
  stages {
    stage('dev') {
      parallel {
        stage('dev') {
          steps {
            echo 'dev stage'
          }
        }

        stage('test') {
          steps {
            echo 'test stage'
          }
        }

        stage('plugin') {
          steps {
            echo 'puling stage'
          }
        }

        stage('QA') {
          steps {
            echo 'qa stage'
          }
        }

        stage('UAT') {
          steps {
            echo 'UAT stage'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy stage'
      }
    }

    stage('operate') {
      steps {
        echo 'operate stage'
      }
    }

  }
}