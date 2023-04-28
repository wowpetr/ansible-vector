pipeline {
    agent {
        label 'linux'
    }
    stages {
        stage('Cloning vector role') {
            steps {
                git branch: 'main', url: 'https://github.com/wowpetr/ansible-vector.git'
            }
        }
        stage('Molecule test') {
            steps {
                sh 'molecule test'
            }
        }
    }
}