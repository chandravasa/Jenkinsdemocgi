pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/SashiDuratech/jenkinsdemocgi.git'
                bat "./mybatch.bat"
            }
        }
        stage('Hello1') {
            steps {
                git 'https://github.com/SashiDuratech/jenkinsdemocgi.git'
                bat "./mybatch1.bat"
            }
        }
    }
}
