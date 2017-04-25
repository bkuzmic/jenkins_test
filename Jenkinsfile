#!groovy
node {
    stage('Source checkout') {
        checkout scm
    }

    stage('Build') {
        echo 'Building....'
    }

    stage('Test') {
        echo 'Building....'
        sh 'sudo mv /bla /error'
    }

    stage('Deploy') {
        echo 'Deploying....'
    }
}