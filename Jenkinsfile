pipeline {
    agent any

    stages {
        stage('SayHello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('SayHi') {
            steps {
                echo 'Hi World - Returning'
            }
        }
        
        stage('LetsBuild') {
            steps {
                echo 'Building'
            }
        }
        stage('LetsTest') {
            steps {
                echo 'Testing'
            }
        }
        stage('LetsDeploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}
