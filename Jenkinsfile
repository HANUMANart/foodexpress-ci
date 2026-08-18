
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'python3 -m pip install pytest'
    }
}
        stage('Test') {
            steps { sh 'pytest' }
        }
    }
}