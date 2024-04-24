pipeline {
    agent {
        node {
            label 'maven-agent'
        }
    }

environment {
    PATH = "/opt/apache-maven-4.0.0/bin:$PATH"
}
    stages {
        stage('build'){
            steps {
                echo '------------------- Build Started -------------'
                sh 'mvn clean deploy'
                echo '------------------- Build Completed -------------'
            }
        }
    }
}
