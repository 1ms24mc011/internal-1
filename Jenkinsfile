pipeline {
    agent any
    stages {
        stage('Print Message') {
            steps {
                script {
                    if (env.BRANCH_NAME == 'master') {
                        echo "hello"
                    } else if (env.BRANCH_NAME == 'dev') {
                        echo "hey"
                    } else {
                        echo "branch name is ${env.BRANCH_NAME}"
                    }
                }
            }
        }
    }
}
