pipeline {
    agent any
    tools {
        maven "Maven2"
        jdk "jdk"
    }
    stages {
        stage('Build') {
            steps {
                
                sh 'mvn install'
                
            }
        }
     }
}
