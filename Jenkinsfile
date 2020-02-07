pipeline {
    agent {
        docker {
            image 'maven:3-alpine'
	    args '-v /root/.m2:/root/.m2'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn --version'
                sh 'ls -lha ~'
		sh 'whoami'
		sh 'ls -lha /home/'
		sh 'touch file.txt'
		sh 'ls -lha /root'

            }
        }
    }
}
