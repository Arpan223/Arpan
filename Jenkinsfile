pipeline {
    agent {
    node {
        label 'Linux'
        customWorkspace '/home/ec2-user'
    }
}
    stages {
        stage ('Checkout') {
            steps {
            sh 'https://github.com/Arpan223/game-of-life.git'
            }
        }
    
        stage ('Build') {
            steps {
            sh 'mvn clean install'
            }
        }
    }
}
