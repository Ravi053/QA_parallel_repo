pipeline {
    agent none;
    
    stages {
        stage('Build') {
            agent {label 'master'}
            steps {
                echo "this is master"
                sh '''
                find . -type f -mtime +90 | rm -rf
                '''
            }
        }
                stage('slave') {
                    agent {label 'label1'}
                    steps {
                        echo "this is slave node"
                        sh '''
                        find . -type f -mtime +90 | rm -rf
                        '''        
            }
        }
    }
}
