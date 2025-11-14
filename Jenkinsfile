pipeline {
    agent any
    triggers {
        githubPush()
    }
    options {
        skipDefaultCheckout(false)  // Всегда делать checkout
    }
    stages {
        stage('Build') {
            steps {
                echo "Build triggered by GitHub push"
                // ваши шаги сборки
            }
        }
    }
}

