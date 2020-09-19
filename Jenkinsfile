node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com ', 'dockerid') {

        def customImage = docker.build("mstarin/project-2020")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
