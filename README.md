# Docker Demo (dd)

Newpath's - 2/26/2017 Meeting & Talk - Docker with David

The slides are included in the `Docker--2-27-2017--Newpath-Talk.pptx` file. Additionally, they can be found on OneDrive [here](https://1drv.ms/p/s!AigG_yCNVYnRoJ1BiVh9WjjGfLwo-g).


# Talk - Keys Points

The reason I wanted to learn Docker was and is for increased development flexability and speed. The ability to instantly switch to a "production" setup is a plus once I can figure out nginx configs...

In the slides and demos below I attempt to showcase using docker to programatically build configurations to meet your needs. As much as I've tried to look for the "holy grail" solution on [Docker Hub](https://hub.docker.com/) understanding what is going on completely cannot be understated. In summary, build a `Dockerfile` that meets your needs and which you completely understand and work from there.

Best Dockerizing all the things!


# Demos

I've included all of the "final" `Dockerfile`s just named differently. Rename them to `Dockerfile` when copying into the repos to run!

1. The basic `Dockerfile` available in [docker-d1](docker-d1/)
2. The React App Demo available in [newpath-react-app-demo](newpath-react-app-demo/)
    1. Learn creating a `Dockerfile` to fit your needs (e.g. @atareshawty's original README)
    2. Using [Docker Hub](https://hub.docker.com/) to make it better?
        - `+` community insight
        - `-` ambiguity & misdirection

3. The Watson TA demo available in [watson-ta](watson-ta/)
4. Want to get crazy? Docker in Docker CRAZY? See [this post](https://blog.docker.com/2013/09/docker-can-now-run-within-docker/). Why? Maybe [this](https://dantehranian.wordpress.com/2014/10/25/building-docker-images-within-docker-containers-via-jenkins/) will help for a usecase ;)
