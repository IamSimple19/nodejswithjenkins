node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerid') {

        def customImage = docker.build("simple1331/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
