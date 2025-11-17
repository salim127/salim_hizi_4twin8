pipeline {
    agent any

    stages {

        stage('Clone from GitHub') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/salim127/salim_hizi_4twin8.git'
            }
        }

        stage('Build Maven Project') {
            steps {
                sh 'mvn compile'
            }
        }
    }
}
