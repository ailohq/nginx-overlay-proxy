# Nginx Overlay Proxy

[![Docker Repository on Quay.io](https://quay.io/repository/trunk/overlay-proxy/status "Docker Repository on Quay.io")](https://quay.io/repository/trunk/overlay-proxy)

Simple Nginx proxy for simple requests into a overlay network.

A typical use case is when using Docker PaaS such as Tutum, to poll health checks
of individual Docker containers inside a overlay network, which are not exposed
at the DNS level.
