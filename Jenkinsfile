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
                 echo 'Deploy Stage'
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
        emailext body: 'Integrating git with email', subject: 'JENKINS', to: 'shettigar2699@gmail.com'
      }
    }
}
