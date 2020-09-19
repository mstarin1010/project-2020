node {

    checkout scm

    docker.withRegistry('https://hub.docker.com, 'mstarin1010') {

        def customImage = docker.build("mstarin/project-2020")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
