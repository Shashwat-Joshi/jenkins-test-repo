pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        git(url: 'https://github.com/Shashwat-Joshi/jenkins-test-repo', poll: true)
        echo 'Commit found'
      }
    }

  }
}