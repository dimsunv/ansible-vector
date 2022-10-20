pipeline {
    agent {
        label 'homework'
    }

    stages {
        stage('Checkout') {
            steps {
                git credentialsId: '708a2ed9-77fb-4669-8244-4a414b5bb9f5', url: 'git@github.com:dimsunv/ansible-vector.git'
            }
        }
        stage('Molecule Test'){
            steps {
                sh 'molecule test -s podman --destroy always'
            }
        }
    }
}
