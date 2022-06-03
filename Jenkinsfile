pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                echo 'Cloning Repo from Github'
                git 'https://github.com/lklima/gnome'
            }
        }
        stage('build') {
            steps {
                echo 'Build steps go here'
            }
        }
        stage('save build logs'){
            steps {
                sh 'cp ${env.BUILD_LOG) /tmp/build_logs'
            }
        }
    }
}