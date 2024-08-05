pipeline {
    agent any
    tools{
        jdk 'java17'
        maven 'maven3'
    }
    stages{
        stage('maven test') {
            steps {
                echo 'mvn clean test'
            }
        }
         stage('maven Build') {
            steps {
                echo 'mvn clean install'
            }
        }
         stage('maven Build 2') {
            steps {
                echo 'mvn clean install'
            }
        }
   }   
}  


