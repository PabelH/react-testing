pipeline {
  agent any
  
  stages {
    stage('Clonar repositorio') {
      steps {
        git 'https://github.com/PabelH/react-testing.git'
      }
    }
    stage('Install') {
      steps {
        
          sh 'npm install'
          
          //sh 'yarn test'
        
      }
    }
  stage('Test') {
      steps {
    
        //  sh 'yarn test'
          sh 'npm run test'
        
      }
    }
  }
}