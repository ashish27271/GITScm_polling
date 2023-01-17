pipeline {
  agent any
  stages {
    stage('GitHub hook trigger') {
      steps {
        git 'https://github.com/ashish27271/GITScm_polling.git'
        sh 'ant clean compile test package war'
          }
    }
  }
}
