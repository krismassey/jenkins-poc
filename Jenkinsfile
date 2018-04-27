node('docker') {

docker.withRegistry('https://registry.hub.docker.com', 'docker-hub-credentials') {
    docker.image('alpine:3.5').inside {

        stage("test") {
          sh "HELLO"
        }
    }
    }

}
