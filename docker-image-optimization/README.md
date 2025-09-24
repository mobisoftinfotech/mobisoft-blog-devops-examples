# Node.js Docker Demo

## How to Build & Run

1. Go to Directory:
    ```bash
    cd docker-image-optimization/demo-nodejs-app
    ```

2. Build the Docker image:
    ```bash
    docker build -t demo-nodejs-app .
    ```

3. Run the container:
    ```bash
    docker run -p 3000:3000 demo-nodejs-app
    ```

4. Access the app at [http://localhost:3000](http://localhost:3000)



# Django Docker Demo

## How to Build & Run

1. Go to Directory:
    ```bash
    cd docker-image-optimization/demo-django-app
    ```

2. Build the Docker image:
    ```bash
    docker build -t demo-django-app .
    ```

3. Run the container:
    ```bash
    docker run -p 8000:8000 demo-django-app
    ```

4. Access the app at [http://localhost:8000](http://localhost:8000)


# Spring Boot Docker Demo

## How to Build & Run

1. Go to Directory:
    ```bash
    cd docker-image-optimization/demo-springboot-app
    ```

2. Build the JAR (if needed):
    ```bash
    mvn clean package
    ```

3. Build the Docker image:
    ```bash
    docker build -t demo-springboot-app .
    ```

4. Run the container:
    ```bash
    docker run -p 8080:8080 demo-springboot-app
    ```

5. Access the app at [http://localhost:8080](http://localhost:8080)
