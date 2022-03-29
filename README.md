# Lernen.Cloud Chatbot

## Training of the Model 

Choose the folder with the chatbot in German (rasa/lernen-cloud-de)

```sh
    rasa train
```

## Usage

### Start the Rasa Server

```sh
    rasa run --enable-api
```

### Start the Action Server

```sh
    cd actions/
    rasa run actions
```

## Docker

In the outer project structure run:

### Docker Compose (de)

```sh
    docker-compose -f docker-compose_de.yml -p lernen-cloud_de up --build
```
