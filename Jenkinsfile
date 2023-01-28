pipeline {
    agent any

    stages {
        stage('BUILD') {
            steps {
                echo 'Build Stage'
            }
        }
        stage('TEST') {
            steps {
                 echo 'Test Stage'
            }
        }
        stage('DEPLOY') {
            steps {
                 echo 'Deployyyyy Stage'
            }
        }
        stage('RELEASE') {
            steps {
                 echo 'Releaseeeeee Stage'
            }
        }
    }
    post{
      always{
        emailext body: 'Integrating git with email', subject: 'JENKINS', to: 'shettigar2699@gmail.com'
      }
    }
}
