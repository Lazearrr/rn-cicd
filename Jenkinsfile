pipeline {
    agent any
    environment {

    }

    stages {
        stage('clone') {
            steps {
                echo 'Cloning Repo from Github'
                git clone 'https://github.com/lklima/gnome'
            }
        }
        stage('build') {
            steps {
                echo 'Build steps go here'
            }
        }
    }
}