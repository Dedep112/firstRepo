pipeline {
    agent any
    stages {
        stage('build') {
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