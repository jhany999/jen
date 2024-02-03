pipeline {
    agent {
        node{
            label 'maven'
        }
    }

    stages {
        stage('clone-git') {
            steps {
               git branch: 'main', url: 'https://github.com/ravdy/tweet-trend-new.git'
            }
        }
    }
}
