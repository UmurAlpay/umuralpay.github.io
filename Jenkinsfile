pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
                input {
                    message "selam"
                    ok "Yes."
                }
            steps {
                echo 'Deploying....'
            }
        }
    }
}
