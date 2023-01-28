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
