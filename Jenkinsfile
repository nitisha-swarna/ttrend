pipeline {
    agent {
        node {
            label 'maven-agent'
        } 
    }
    stages {
        stage ('clone code') {
            steps {
                git branch: 'main', url: 'https://github.com/nitisha-swarna/ttrend.git'
            }
        }
    }
}
