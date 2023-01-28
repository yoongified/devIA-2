pipeline {
    agent any

    stages {
        stage('BUILD') {
            steps {
                echo 'Buillllld Stage'
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
    }
    post{
      always{
        emailext body: 'tESTING WEBHOOK git with email', subject: 'JENKINS', to: 'shettigar2699@gmail.com'
      }
    }
}
