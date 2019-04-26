# Toylatte
## Starting the application
1. Install Docker
2. Run ``docker-compose build``
    - This will run the commands to build the image in docker/ folder
3. Run ``docker-compose up -d``
    - This will start the container. The -d flag means to start it and run without blocking.
    - To show the logs...run ``docker-compose logs``
    - To show the containers running ``docker-compose ps``
4. Verify that the app is running by going to ``localhost:5000`` and you should expect a response
