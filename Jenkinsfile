pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/tiwudickson/tweet-trend-new.git'
            }
        }
    }
}
