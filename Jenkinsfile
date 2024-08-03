pipeline {
    agent {
       docker { image 'node:16-alpine' } 
    }
    stages {
        stages('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}