pipeline {
    agent none;
    
    stages {
        stage('Build') {
            agent {label 'master'}
            steps {
                echo "this is master"
                sh '''
                find cd / -mtime +60 |xargs rm
                '''
            }
        }
                stage('slave') {
                    agent {label 'label1'}
                    steps {
                        echo "this is slave node"
                        sh '''
                        find cd / -mtime +90 | xargs rm
                        '''        
            }
        }
    }
}
