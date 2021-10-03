pipeline {
  agent {CentOS-client-slave}
  stages {
    stage ('build') {
      steps {
          echo 'SB is building first project...'
      }
    }
    stage ('deploy') {
      steps {
          echo 'This stage will Deploy the SB project...'
      }
    }
    stage ('test') {
      steps {
          echo 'Testing phase...'
      }
    }
    stage ('release') {
      steps {
          echo 'Release successful build to the customers...'
      }
    }
  }
}
