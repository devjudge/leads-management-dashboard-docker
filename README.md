1. This is a dockerized Leads Management Angular Dashboard

2. To run the sample code, do the following:

    Go to the directory which contains the Dockerfile
    Run the following commands in the terminal/command line:    
    - docker build -t leads:angular .
    - docker run -v ${PWD}:/app -v /app/node_modules -p 4201:4200 --rm leads:angular
    
3. Go to http://localhost:4201/ in your browser to view it.