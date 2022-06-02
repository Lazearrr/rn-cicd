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
            echo 'Building using Gradle'
        }
    }
}