pipeline {
    agent any
    environment {
        GIT_USERNAME = 'Lazearrr'
        GIT_PASSWORD = 'Lowdog541.'

    }

    stages {
        stage('clone') {
            steps {
                echo 'Cloning Repo from Github'
                sh("""
                git config --global credential.username ${GIT_USERNAME}
                git config --global credential.password ${GIT_PASSWORD}
                git clone https://github.com/lklima/gnome.git
                """)
            }
        }
        stage('build') {
            steps {
                echo 'Build steps go here'
            }
        }
    }
}