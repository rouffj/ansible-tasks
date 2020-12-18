pipeline {
    agent any
    /*
    agent {
        docker { image 'node:14-alpine' }
    }
    */

    stages {
        stage('Lint') {
            steps {
                echo 'ansible-lint'
            }
        }
        
        stage('Tests') {
            steps {
                echo 'Testing'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}
