node {

    checkout scm

    docker.withRegistry('mstarin1010/project-2020 ', 'dockerid') {

        def customImage = docker.build("mstarin/project-2020")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
