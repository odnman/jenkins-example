/* Requires the Docker Pipeline plugin */
node {
    stage('Build') {
        docker.image('node:16.17.1-alpine').inside {
            sh 'node --version'
        }
    }
}