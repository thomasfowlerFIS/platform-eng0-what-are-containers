# What are Containers

Containers are a way of packaging code so that it can be run across different hardware and operating systems.

We can easily create containers if we have a definition of operating system libraries and dependencies for our application code. The definition can be used by containerization software (Docker) to start isolated containers.

![Container diagram](https://raw.githubusercontent.com/thomasfowlerFIS/platform-eng0-what-are-containers/master/diagram-1.png)

Notice that we’re not emulating an entire guest OS like we do with virtual machines. We can install Docker on Linux, Mac, and Windows machines which allows us to run our containers across all these different operating systems.

Containers are completely self-contained, use minimal resources, and can communicate with other containers or networks only when we explicitly set up the ports.

This level of isolation allows us to quickly start containers, run many of them on a single host, set up automatic scaling, and build automation tools.

## Shipping Container Analogy

It used to take days to load and unload cargo before the invention of intermodal or shipping containers. Take a look at this picture of mixed cargo being loaded onto a ship circa 1927.

![By Unknown author - State Library of South Australia, available at [http://collections.slsa.sa.gov.au/resource/B+4433](http://collections.slsa.sa.gov.au/resource/B+4433), Public Domain, [https://commons.wikimedia.org/w/index.php?curid=36468603](https://commons.wikimedia.org/w/index.php?curid=36468603)](https://raw.githubusercontent.com/thomasfowlerFIS/platform-eng0-what-are-containers/master/ship.png)

By Unknown author - State Library of South Australia, available at [http://collections.slsa.sa.gov.au/resource/B+4433](http://collections.slsa.sa.gov.au/resource/B+4433), Public Domain, [https://commons.wikimedia.org/w/index.php?curid=36468603](https://commons.wikimedia.org/w/index.php?curid=36468603)

Each cargo has a unique size, shape, and handling requirement. It would be nightmare to create  standard equipments for handling all the different types of cargo.

![By KMJ, CC BY-SA 3.0, [https://commons.wikimedia.org/w/index.php?curid=1443327](https://commons.wikimedia.org/w/index.php?curid=1443327)](https://raw.githubusercontent.com/thomasfowlerFIS/platform-eng0-what-are-containers/master/container.png)

By KMJ, CC BY-SA 3.0, [https://commons.wikimedia.org/w/index.php?curid=1443327](https://commons.wikimedia.org/w/index.php?curid=1443327)

The shipping container standardized the way we package cargo and paved the way for standardized equipments. These are boxes with standard dimensions which can be filled with whatever goods we want. Shipping equipments and transports can be designed to only account for a container’s standard dimension instead of a worrying about a dizzying variety of possibilities.

## Back to Containers

Software containers work similarly in that we can put our application code, os libraries, and dependencies in a container which can then be handled by standardized tools. We don’t have to worry about our code breaking when it’s run on a different machine than ours!
