pipeline {
    agent any 
    stages {
        stage('Clean') { 
            steps {
                sh "mvn clean"      
                
            }
        }
         stage('Clean') { 
            steps {
                sh "mvn clean"      
                
            }
        }
        stage('Test') { 
            steps {
                sh "mvn test"
            }
        }
        stage('Deploy') { 
            steps {
                sh "mvn package"
            }
        }
        stage('Archiving') { 
            steps {
                archiveArtifacts '**/target/*.jar'
            }
        }
    }
}
