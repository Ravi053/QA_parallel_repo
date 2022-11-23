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
                stage('Test') {
                    steps {
                        echo "this is test stage"
                        sh '''
                        sleep 3
                        '''
            }
        }
    }
}
