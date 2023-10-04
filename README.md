# chatgpt
Integrating ChatGPT into our Django project


## Repository
Clone or pull from the dev branch before you begin coding.
```

***
***



## Environment variable and secrets
1. Create a .env file from .env.template
    ```
    #Unix and MacOS
    cd backend && cp .env.template .env

    #windows
    cd sandbox && copy .env.template .env
    ```

2. Add your ChatGPT api key tha can be found [here](https://platform.openai.com/account/api-keys)

***
***

## Fire up Docker:

>Note: You will need to make sure Docker is running on your machine!

Use the following command to build the docker images:
```
docker-compose  up -d --build
```

Alternatively, If you have [make](https://platform.openai.com/account/api-keys) installed, you can run the following command:
```
make build
```

### Finished
You should now be up and running!

* The web app is running on  http://localhost:8000

***
***

### References
This project is based on the official ChatGPT quick-start tutorial that can be found [here](https://platform.openai.com/docs/quickstart/build-your-application)

