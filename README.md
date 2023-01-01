DOCKERFILE
When we have to create our own image we use Dockerfile as default filename.
It is case sensitive.
To execute Dockerfile we use command : Docker build --no-cache . [It will create extra layer upon old modification and will build new and latest modification].
Attributes of Dockerfile:
FROM - To pull images and can be write multiple times.
RUN - To install any service.
CMD -  Specifies the instruction that is to be executed when a Docker container starts and can write once.
ARG - Variables are set and can write once use multiple times.
ENTRYPOINT - Used for command and shell script.
WORDIR - Define the working directory of a Docker container.
COPY - When we want file from home to Docker we use COPY.
ADD -  Same as COPY but when want zip or tar file we use ADD.
VOLUME - Create a new volume.
EXPOSE - Ports are maped or open.
ENV - To set and enviornmental variable.
