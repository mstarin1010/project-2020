node {

    checkout scm

    docker.withRegistry('https://hub.docker.com/u/mstarin1010 ', 'dockerid') {

        def customImage = docker.build("mstarin/project-2020")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
