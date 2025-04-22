pipeline {
    agent any
    
    tools {
      maven 'maven3.9.9'
      jdk 'jdk11'
    }
    
    stages {
        stage('Git Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/SunilVeeravalli/DevOps-BoardGame.git'
                sh "mvn package"
            }
        }
    }
}
