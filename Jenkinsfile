pipeline {
       agent {
                docker {
                    image 'jenkins/jenkins'
                }
            }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
            }
        }
    }
}
