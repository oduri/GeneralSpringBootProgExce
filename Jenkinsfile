pipeline {
    agent any

    tools {

        maven "MAVEN"
        
    }
    
    stages {
        stage('Git clone') {
           steps {
               git changelog: false, credentialsId: 'Gitcredentials', poll: false, url: 'https://github.com/oduri/GeneralSpringBootProgExce.git'
           }
        }
    }
}
