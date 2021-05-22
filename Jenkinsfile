pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
              // Get some code from a GitHub repository
              git 'https://github.com/narmada12345/batch1.git'  
            }
        }
        stage('install') {
            steps {
              // Get some code from a GitHub repository
              sh 'sudo ansibl-plybook webserver.yml --private-key=/home/ubuntu/.ssh/id_rsa'
            }
        }
  
        
    } 
    
 }
