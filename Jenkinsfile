pipeline {
    agent any
    stage('Building a stage') {
        steps {
            withAWS(credentials: 'awscreds', region: 'us-east-2') {
                sh 'echo building a builld'
            }
        }
    }
}
