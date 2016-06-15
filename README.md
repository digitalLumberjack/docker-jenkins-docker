docker-jenkins-docker
======
Run a jenkins server with docker installed, so you can use docker run commands in shell steps.

Start the container with : 
``` 
sudo docker run -v /var/run/docker.sock:/var/run/docker.sock -p 8080:8080 digitallumberjack/docker-jenkins-docker
```

Remember taht if you share volumes like -v /hostdir:/containerdir, the hostdir is on the host, not on the jenkins container.
