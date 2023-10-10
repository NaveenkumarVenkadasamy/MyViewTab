pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo 'Hello World'
                bat 'atlas-compile'
            }
        }
        stage('Package') {
            steps {
                echo 'Hello World'
                bat 'atlas-package'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World'
                bat 'atlas-install-plugin --username naveenececit --password Kanagama@41 --server localhost --http-port 7070 --plugin-key com.atlassian.jira.jira-api --context-path ""'
             }
        }
    }

}