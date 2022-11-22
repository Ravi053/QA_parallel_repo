pipeline {
    agent any;
    stages {
        stage('Build') {
            steps {
                echo "this is build stage"
                sh '''
                sleep 3
                '''
            }
        }
        stage('Print') {
            agent any;
            steps {
                echo "this is build stage"
                sh '''
                sleep 3
                '''
    }
}
          stage('job_name') {
              agent{label 'label1'}
             steps {
                echo "this is build stage"
                 
                
            }
          }
    }
}
