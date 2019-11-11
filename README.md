#### Docker-Compose Example with nginx and php

###### Startup
Download repository and type in:

```bash
# starts the services 
docker-compose up -d
```

Place your websitecontent with *.php or *.html files into the sites/ directory.

---
###### Shutdown
To stop the service and delete the images type in:
```bash
docker-compose down --rmi all
```

