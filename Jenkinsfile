node {
  agent any 
  stages {
    stage('Install') {
      steps { sh 'npm install' }
    }


    stage('Build') {
      steps { sh 'npm run ng serve' }
    }
  
}
