pipeline {
    agent any
    stages {
        stage(' HTML') {
            steps {
                sh 'echo "Hello World with HTML"'
            }
        }
        stage('Upload to AWS') {
            steps {
		    sh 'echo "Hello World with AWS creds"'
            }
        }
    }
}
