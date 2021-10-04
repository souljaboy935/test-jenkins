pipeline {
  agent any
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
        sh 'lsblk'
      }
    }
    stage ('release') {
      steps {
          echo 'Release successful build to the customers...'
        mail bcc: '', body: 'This was sent automatically after building, your software is ready', cc: '', from: '', replyTo: '', subject: 'Sent from Jenkins', to: 'soulja@host1.ansible.com'
      }
    }
  }
}
