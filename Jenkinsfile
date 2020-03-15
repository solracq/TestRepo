pipeline {
  agent any
  
  stages {
    stage('Build'){
      steps {
      	echo 'Building...'
        build job: 'Python_Examples' 
      }
    }
    stage('Test') {
      steps { 
      	echo 'Testing...'
        bat 'dir' 
      }
    }
    stage('Deploy') {
      steps { 
      	echo 'Deploying...'
        bat 'dir' 
      }
    }
  }
}
