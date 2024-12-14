pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/AishwaryaL0722/CI_CD_Pipeline.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                //Add your build commands here
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                //Add your test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                //Add your deployment commands here
            }
        }
    }
}



