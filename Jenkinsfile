pipeline {
    agent any
stages {
        stage("clone code") {
            steps {
                script {
                    // Let's clone the source
                    git 'https://github.com/lilfrou/selenium.git';
                }
            }
        }
    stage('compile stage') {
             steps {
              sh "mvn clean compile" 
        }
    }  
     }
    }  
