pipeline {
    agent any

    stages {
        stage('git checkout') {
            steps {
                git credentialsId: 'Gitcrd', url: 'https://github.com/sufiyan440/Test.git'
            }
        }
    }
}
