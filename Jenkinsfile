pipeline {
  agent none
  stages {
    stage('clone') {
      steps {
        git(url: 'https://github.com/catenoid-company/wrController.git', branch: 'demo-jenkins', poll: true)
      }
    }

  }
}