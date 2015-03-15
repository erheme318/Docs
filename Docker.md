## What is docker ?

Docker is an open platform for developers and sysadmins to build, ship, and run distributed applications. 

- `ENTRYPOINT` makes your dockerized application behave like a binary


### Docker file best practices

1. Keep common instructions at the top of the Dockerfile to utilize the cache.
2. Always pass `-t` to tag the resulting image.
3. Never map the public port in a Dockerfile.
4. Always use the array when using CMD and ENTRYPOINT.
5. ENTRYPOINT and CMD better together.

6. Updates will be baked into the based images you don't need to `apt-get upgrade` in your containers. Keep the image as `one source of truth`.
7. Use small base images
8. Use specific tags
9. Group common operations:
  - Take advantage of the `\` to span multiple lines on your installs 
```
RUN apt-get update && apt-get install -y \
    git \
    libxml2-dev \
    python \
    build-essential \
    make \
```

10. Use your own base images



### Some other suggestions or ideas

1. Only run one process per container 
2. Treat containers at the same level as processes and not as machines.
3. Think of each container as providing a separate service. This will help with future scalability concerns.


### References:
1. http://crosbymichael.com/dockerfile-best-practices.html
2. http://crosbymichael.com/dockerfile-best-practices-take-2.html
