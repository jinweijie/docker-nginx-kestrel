# ASP.NET Core HTTPS & Load balancing
Deploy an ASP.NET Core application with HTTPS & Load balancing using Docker and NGINX as reverse proxy.

To get started:

```bash
    docker-compose build
    docker-compose scale core-app=4
    docker-compose up
```

IMPORTANT: Due to NGINX (Free version) limiations, current configuration is set to work with a fixed scale of 4 nodes.
With NGINX Plus, additional changes might be applied to scale up and down dynamically.