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
          stage('Node') {
              agent {label 'label1'}
            steps {
                echo "this is build stage"
                sh '''
                du -sh
                '''
            }
          }
        
        stage('Process') {
            steps {
                echo "this is process stage"
                sh '''
                ps -ef
                '''
            }
        }
    }
}
        
