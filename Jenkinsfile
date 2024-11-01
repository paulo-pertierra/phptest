pipeline {
  agent {
    node {
      label 'gcp'
    }

  }
  stages {
    stage('pull') {
      steps {
        git(url: 'https://github.com/paulo-pertierra/phptest', branch: 'main')
      }
    }

    stage('') {
      steps {
        echo 'Test'
      }
    }

  }
}