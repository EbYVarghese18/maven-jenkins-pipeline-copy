pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build'
                mvn package
                java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver'
            }
        }
    }
}