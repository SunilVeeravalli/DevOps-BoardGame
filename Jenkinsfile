pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/SunilVeeravalli/DevOps-BoardGame.git'
            }
        }

        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('OS details') {
            steps {
                echo 'The OS that is being used:'
                sh 'uname -a'
            }
        }
    }
}
