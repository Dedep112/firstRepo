pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Compiling'
                echo 'Testing'
                echo 'Package'
            }
        }
        stage('Archive') {
            steps {
                echo 'Archive'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}