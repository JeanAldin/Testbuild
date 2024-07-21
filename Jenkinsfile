pipeline {
    agent any

    

    stages {
        stage('checkout') {
            steps {
                checkout scm
            }
        }
        
        stage('Test') {
            steps {
            sh './home/rojo/Projet vscode/Nodejenkins/test/mytest.test.js'
'
          
            }
        }

    

        stage('Build') {
            steps {
                
             sh 'npm run build'
               
}
            }
        }

        
    }
