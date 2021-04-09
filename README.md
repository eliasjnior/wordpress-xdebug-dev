# WordPress with Xdebug

This is a simple Docker environment to be able to use Xdebug with WordPress. It uses the latest version of WordPress and latest version of Xdebug.

## How to start

Simply run the following command to start the server:

```
docker-compose up
```

The application will be ready and you can setup your WordPress installation. You can check the WordPress files inside the `html` folder that will be created and the logs inside `logs` folder.

## Debugging

The config file is already setup for VSCode, so it's just "Listen for Xdebug" in debug tab.