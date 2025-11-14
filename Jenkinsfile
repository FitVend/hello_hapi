pipeline {
    agent any
    triggers {
        githubPush()
    }
    options {
        skipDefaultCheckout(true)
    }
    stages {
        stage('Checkout') {
            steps {
                git branch: 'master', 
                    url: 'https://github.com/FitVend/hello_hapi.git'
                echo "Changes detected - building..."
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // ваши шаги сборки
            }
        }
    }
}
