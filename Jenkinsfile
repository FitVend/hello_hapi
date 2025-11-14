pipeline {
    agent any
    
    triggers {
        pollSCM('')  // Отключает polling, полагается только на webhook
        // или
        githubPush()
    }
    
    options {
        githubProjectProperty(projectUrlStr: 'https://github.com/your-user/your-repo')
    }
    
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}
