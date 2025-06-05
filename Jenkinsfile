pipeline {
    agent Agent

    stages {
        stage('build') {
            steps {
                echo 'This is build stage'
                sh 'touch buildfile.txt'
            }
        }
      stage('test') {
            steps {
                echo 'This is test stage'
                sh 'touch testfile.txt'
            }
        }
      stage('deploy') {
            steps {
                echo 'This is deploy stage'                
                sh 'touch deployfile.txt'

            }
        }
    }
}
