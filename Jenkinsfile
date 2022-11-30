pipeline {
    agent any

    stages {
        stage('Stage1') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Approver') {
            steps {
             input 'Approve'   
            }
        }
        stage('stage2') {
            steps {
                echo 'testing pipeline'
            }
        }
    }
}
