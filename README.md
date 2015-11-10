# docker-minimal
This Dockerfile creates minimalistic image which is useful as a base for data volume containers.
The new data volume can be created by this command:

    docker create -v /DESIRED/PATH --name CONTAINER_NAME r2dev/minimal /

See [docker documentation](http://docs.docker.com/engine/userguide/dockervolumes/#creating-and-mounting-a-data-volume-container) for more info about data volume containers.

