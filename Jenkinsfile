pipeline {
    agent any

    stages {
        stage('git-hub') {
            steps {
                git branch: 'main', url: 'https://github.com/Sai-Jaishnavi27/spring-petclinic.git'
            }
        }
        stage('build generate') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
