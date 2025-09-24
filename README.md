# mobisoft-blog-devops-examples
Git repo for examples for devops blogs for mobisoftinfotech.com

# Node.js Docker Demo

## How to Build & Run

1. Clone the repository:

    git clone git@github.com:mobisoftinfotech/mobisoft-blog-devops-examples.git
    
    cd docker-image-optimization/demo-nodejs-app


2. Build the Docker image:

    docker build -t demo-nodejs-app .


3. Run the container:

    docker run -p 3000:3000 demo-nodejs-app


4. Access the app at [http://localhost:3000](http://localhost:3000)


# Django Docker Demo

## How to Build & Run

1. Clone the repository:

    git clone git@github.com:mobisoftinfotech/mobisoft-blog-devops-examples.git
    
    cd docker-image-optimization/demo-django-app


2. Build the Docker image:

    docker build -t demo-django-app .


3. Run the container:

    docker run -p 8000:8000 demo-django-app


4. Access the app at [http://localhost:8000](http://localhost:8000)


# Spring Boot Docker Demo

## How to Build & Run

1. Clone the repository:

    git clone git@github.com:mobisoftinfotech/mobisoft-blog-devops-examples.git
    
    cd docker-image-optimization/demo-springboot-app


2. Build the JAR (if needed):

    ./mvnw clean package


3. Build the Docker image:

    docker build -t demo-springboot-app .


4. Run the container:

    docker run -p 8080:8080 demo-springboot-app


5. Access the app at [http://localhost:8080](http://localhost:8080)
