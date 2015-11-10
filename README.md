# docker-minimal
This Dockerfile creates minimalistic image which is useful as a base for data volume containers.

You can create new data volume container by this command:

docker create -v /DESIRED/PATH --name CONTAINER_NAME vaclavv/minimal /

See http://docs.docker.com/engine/userguide/dockervolumes/#creating-and-mounting-a-data-volume-container

