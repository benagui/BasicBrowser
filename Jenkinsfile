pipeline {
  agent any
  stages {
    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            echo 'sss'
          }
        }

        stage('test2') {
          steps {
            echo 's'
          }
        }

      }
    }

    stage('s2') {
      parallel {
        stage('s2') {
          steps {
            echo 's2'
          }
        }

        stage('s3') {
          steps {
            echo 's3'
          }
        }

      }
    }

  }
}