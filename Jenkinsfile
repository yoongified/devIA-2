pipeline {
    agent any

    stages {
        stage('BUILD') {
            steps {
                echo 'BuilDDDDd Stage'
            }
        }
        stage('TEST') {
            steps {
                 echo 'Testttttt Stage'
            }
        }
        stage('DEPLOY') {
            steps {
                 echo 'Deployyyyy Stage'
            }
        }
        stage('RELEASE') {
            steps {
                 echo 'Release Stage'
            }
        }
    }
    post{
      always{
        emailext body: 'tESTING WEBHOOK git with email', subject: 'JENKINS', to: 'shettigar2699@gmail.com'
      }
    }
}
