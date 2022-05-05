pipeline {
    agent {
        docker { image 'cimg/node:18.0.0-browsers' }
    }
    stages {
        stage('Test') {
            steps {
                npm install
		npm run test
            }
        }
    }
}