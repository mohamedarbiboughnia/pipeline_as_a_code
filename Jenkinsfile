pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build complited'
        timeout(time: 5, unit: 'SECONDS') {
         sh 'sleep 10'
       }
      }
    }
    stage('test') {
      steps {
        echo 'test complited'
      }
    }
    stage('deploy') {
      steps {
        echo 'deploy complited'
      }
    }

  }
}