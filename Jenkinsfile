node {
  stage('check') { 
       git branche : 'master', url:'https://github.com/Amira1502/devops-angular'
    }
    stage('Build') { 
       sh "npm install"
    }
    stage('Test') { 
        sh "npm run build:ssr"
    }
    stage('Deploy') { 
       sh "npm run ng serve"
    }
}
