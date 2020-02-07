pipeline {
    agent {
        docker {
            image 'maven:3-alpine'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn --version'
                sh 'ls -lha ~'
		sh 'whoami'
		sh 'ls -lha /home/'
		sh 'echo show root directory'
		sh 'ls -lha /root'
            }
        }
    }
}
