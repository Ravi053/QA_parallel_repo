pipeline {
    agent none;
    parameters {
  booleanParam description: 'check status', name: 'status'
}
    stages {
        stage('Build') {
            agent {label 'label1'}
            steps {
                echo "this is build stage"
                sh '''
                ps -ef
                '''
            }
        }
                stage('Test') {
                    agent {label 'label1'}
                    steps {
                        echo "this is test stage"
                        sh '''
                        df -h
                        '''
                    }
                }
                        stage('Deploy') {
                            steps {
                                echo "this is Deploy stage"
                            
            }
        }
    }
}
