docker-tor
==========

A docker'ized internal-only tor relay.

Modified to allow use as a tor socks proxy for your lan.

example usage:

    docker build -t cwoac/tor .
    docker run -d -p 0.0.0.0:9001:9001 -p 0.0.0.0:9050:9050 cwoac/tor`
