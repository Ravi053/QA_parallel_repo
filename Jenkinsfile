pipeline {
    agent none;
    stages {
        stage('Build') {
            agent {label 'label1'}
            steps {
                echo "this is build stage"
                sh '''
                sleep 3
                '''
            }
        }
                stage('Test') {
                    agent {label 'label1'}
                    steps {
                        echo "this is test stage"
                        sh '''
                        sleep 3
                        '''
                    }
                }
                        stage('Deploy') {
                            agent {label 'label'}
                            steps {
                                echo "this is Deploy stage"
                            
            }
        }
    }
}
