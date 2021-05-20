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
              sh 'sudo apt update'
              sh 'sudo apt install maven -y'
            }
        }
        stage('Build') {
            steps {
              // Run Maven on a Unix agent.
              sh "mvn clean package -DskipTests clean package"
            }
        }
        
    } 
    
 }
