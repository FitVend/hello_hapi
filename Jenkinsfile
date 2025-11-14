pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Force Build') {
            steps {
                echo "GitHub push detected - building regardless of changes"
                // ваши шаги сборки
            }
        }
    }
}


