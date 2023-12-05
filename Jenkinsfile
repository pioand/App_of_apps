def frontendImage="pioand/frontend"
def backendImage="pioand/backend"
def dockerRegistry=""
def registryCredentials="dockerhub" 

pipeline {
    agent {
      label 'agent'
    }
    stages {
        stage('Get Code') {
            steps {
                checkout scm
            }
        }
    }
}
