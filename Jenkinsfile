pipeline {
    agent any
    // environment {
        // SCANNER_HOME='/opt/sonarscanner/sonarscanner'
    // }

    stages {
        stage('Hello') {
            steps {
                echo 'pipeline started'
                sh 'ls'
            }
        }
        stage('git clone'){
            steps {
                sh 'git clone https://github.com/Aakibgithuber/deployment-of-youtube.git'
            }
        }
    }

}
