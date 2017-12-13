
## Run:

    docker-compose up --force-recreate

## Test:
    
    curl https://domain.example.com/
    Hello app!!
    docker-compose kill app
    curl https://domain.example.com/
    Maintenance page
    docker-compose start app
    curl https://domain.example.com/
    Hello app!!
