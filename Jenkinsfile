/* Requires the Docker Pipeline plugin */
node {
    stage('Build') {
        docker.image('maven:3.9.4-eclipse-temurin-17-alpine').inside {
            sh 'mvn --version'
        }
    }
}