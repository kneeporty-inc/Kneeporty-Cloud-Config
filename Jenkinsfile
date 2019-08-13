pipeline {
    agent {
        label "java8"
    }
    stages {
        stage('Clean and package') {
            steps {
                echo "Running build ${env.BUILD_ID}"
                bat 'mvn -DskipTests clean package'
            }
        }
    }
}