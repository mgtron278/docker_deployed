# docker_deployed

# What all are required?

1. Github account
2. VS code IDE
3. Heroku account
4. Github CLI

Create a new environment for the project, with this command: 
    conda create -p env_name python==3.10

To active this specific environment:

    ...
    conda activate env_name/
    ...
 ** NOTE **
        Be careful while creating your procfile. Flask applications 
        would require this specific command (web: gunicorn app:app)
        and installation of gunicorn package to get deployed on
        heroku
        
