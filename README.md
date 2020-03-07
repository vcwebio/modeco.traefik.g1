# `traefik.g1` - Modeco

Traefik provides autodiscovery for the services exposed by the modules.  
See `conteco.docs.overview` for more information on the ModEco ecosystem.

## Structure

The module consists of the following service stack:

 * traefik - Traefik

Traefik is configured to expose a dashboard on port 8080.  
The HTTP services are exposed on port 80 using a URL based scheme.
TCP services, if required, are exposed on specific ports.
