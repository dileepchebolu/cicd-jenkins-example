pipeline {
    agent any
    tools{
       maven 'hellomaven'
      }
    stages {
        stage ('Build') {
            steps {
                sh 'mvn clean package'
                }
            }
        }
}
