pipeline {
    agent {
    node {
        label 'built-in'
        customWorkspace '/home/ec2-user'
    }
}    
    stages {
        stage ('Checkout') {
            steps {
                sh 'git clone https://github.com/Arpan223/game-of-life.git'
            }
        }
    }    
}
