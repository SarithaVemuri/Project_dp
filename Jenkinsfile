pipeline {
    agent {
        node {
            label 'maven-agent'
        }
    }

    stages {
        stage('Clone the code') {
            steps {
                git branch: 'main', url: 'https://github.com/SarithaVemuri/Project_dp.git'
            }
        }
    }
}

