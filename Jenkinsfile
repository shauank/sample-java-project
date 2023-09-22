@Library('my-shared-library@main') _

pipeline {
    agent any
    tools {
        maven 'maven 3.9.4' 
    }
    
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
