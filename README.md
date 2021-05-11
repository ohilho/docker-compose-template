# docker-compose-template
docker compose github repository template 

## Introduction
### Directory structure

- ./copy - all files under this directory will be copied to the /root/
- ./copy/run.sh - container will run this shell script
- ./copy/requirements.txt - pip requirement.txt file
- ./docker-compose-yml -docker compose will run container based on this file
- ./LICENSE - repo license
- ./README.md - this file
- ./template.env - template for the .env file. this is environment variable for docker-compose

### Build
- first, customize the 'template.env' and rename the 'template.env' to the '.env'
- run this command
    ```
    docker-compose build
    ```

### Run
- for interactive mode, run this command
    ```
    docker-compose up
    ```
- or if you want daemon, run this command
    ```
    docker-compose up -d
    ```


