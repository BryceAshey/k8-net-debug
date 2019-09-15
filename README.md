# k8s-net-debug
A Docker container hosting a bunch of network debugging tools - very handy for debugging network problems in kubernetes.

Full credit goes to [Sasha Klizhentas' article](https://gravitational.com/blog/troubleshooting-kubernetes-networking/) on debugging kubernetes for the basis of this image.

Currently contains the following tools:
- iproute2 
- net-tools 
- ethtool 
- nano 
- dnsutils

The container also runs a simple HTTP server on port 5000 for testing purposes.

Docker image available on the [Docker public hub](https://hub.docker.com/r/bryceashey/k8s-net-debug)