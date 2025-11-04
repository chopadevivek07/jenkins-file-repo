pipeline {
    agent any

    stages {
        stage('pull') {
            steps {
                git branch: 'main', url: 'https://github.com/chopadevivek07/-Task-Manager---Flask-RDS.git'
            }
        }

        stage('build') {
            steps {
                echo 'build-job'
            }
        }

        stage('test') {
            steps {
                echo 'test-job'
            }
        }

        stage('deploy') {
            steps {
                echo 'deploy-job'
            }
        }
    }
}
