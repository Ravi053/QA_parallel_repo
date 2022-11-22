pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "this is build stage"
            }
        }
        stage('Print') {
            steps {
                echo "this is build stage"
    }
}
          stage('$job_name') {
              agent{label 'label1'}
             steps {
                echo "this is build stage"
                 sh '''
                 df -h
                 '''
                
            }
          }
    }
}
