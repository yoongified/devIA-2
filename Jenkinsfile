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
                 echo 'DeployYYY Stage'
            }
        }
        stage('RELEASE') {
            steps {
                 echo 'Release Stage'
            }
        }
        stage('ZZZZ') {
            steps {
                 echo 'Releeeeeeeease Stage'
            }
        }
    }
    post{
      always{
        emailext body: 'TESTING WEBHOOK git with email', subject: 'JENKINS', to: 'shettigar2699@gmail.com'
      }
    }
}
