# Introduction-to-podman
A container is an encapsulated process that includes the required runtime dependencies for the program to run.
A container engine creates a union file system by merging container image layers.
VM's are heavy is size but containers are lightweight..!!

Container vs Container Image

A container is an isolated runtime environment where applications are executed as isolated processes.

A container image contains a packaged version of your application, with all the dependencies necessary for the application to run.

Running and Displaying Containers

user@host ~]$ podman run registry.redhat.io/rhel7/rhel:7.9 echo 'Red Hat'
Red Hat


WE can use the -p option to map a port in your local machine to a port inside the container. This way, the traffic in your local port is forwarded to the port inside the container, thus, allowing you to access the application from your computer.


