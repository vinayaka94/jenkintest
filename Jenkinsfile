pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Hello World Build Step'
            }
        }
        stage('Trigger downstream job') {
            steps {
                build 'dowstreamjob'
            }
        }
    }
}
