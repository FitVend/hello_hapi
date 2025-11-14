pipeline {
    agent any
    
    triggers {
        pollSCM('')  // Отключает polling, полагается только на webhook
        // или
        githubPush()
    }
    
    options {
        githubProjectProperty(projectUrlStr: 'https://github.com/FitVend/hello_hapi/')
    }
    
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}

