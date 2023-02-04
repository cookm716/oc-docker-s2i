# simple dockerfile to test OCP s2i using Dockerfile 

FROM registry.access.redhat.com/ubi7:latest

CMD ["/bin/bash", "-c", "sleep infinity"]
# altering CMD below to remove comment and make executable
CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
