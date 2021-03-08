Base docker configuration for Symfony / Laravel projects. 

Copy all docker files (including `docker/` folder) into project.

Available commands:

```
Run the app (access on 127.0.0.1:80)           | docker-compose up
Run the app in xdebug (access on 127.0.0.8001) | docker-compose -f docker-compose-xdebug.yml up
Run composer                                   | docker-compose -f docker-compose-cmd.yml composer <install|update|require>
Run tests                                      | docker-compose -f docker-compose-cmd.yml run tests_unit
```



