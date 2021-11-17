pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
               bat "C:/Progra~1/apache-maven-3.6.1/bin/mvn clean"
            }
        }
        stage('--test--') {
            steps {
                bat "C:/Progra~1/apache-maven-3.6.1/bin/mvn test"
            }
        }
        stage('--package--') {
            steps {
                bat "C:/Progra~1/apache-maven-3.6.1/bin/mvn package"
            }
        }
    }
}
