pipeline {
    agent any
    }
 environment {
        // Define the Maven installation (if not defined in Jenkins Global Tools Configuration)
        // For example:
        // MAVEN_HOME = '/path/to/your/maven'
         PATH = "/opt/homebrew/Cellar/maven/3.9.5/libexec"
    }
    
    stages{
        stage('git-checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/srijyothsna5354/devops-automation.git'
            }
           
            }
        stage('mvn-build'){
            steps{
                sh 'mvn clean install'
            }
           
            }
        }
        
        
       
        
