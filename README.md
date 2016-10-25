## Docker container to run Jenkins Slave via JNLP Agent

## What is this ?
Docker container built with CentOS 7, Java, Git to run a Jenkins Slave.

These are the Docker Hub autobuild images located [here](https://hub.docker.com/r/locnh/jenkins-slave/).

![Jenkins Docker](https://media.licdn.com/mpr/mpr/AAEAAQAAAAAAAALDAAAAJDBiZjJiNGQ0LTdkZWUtNDFjOS1hZWU0LWRiMWI5YzQ5OTljNA.png)

## How to start
### The Simplest way
1. Pull the latest image

  ```
  $ docker pull locnh/jenkins-slave
  ```

2. Create container

  ```
  $ docker run --name jenkins-slave -e JNLPURL=<jnlpUrl> -e SECRET=<secret> -d locnh/jenkins-slave

  ```

That's it !

## Contribute
1. Fork me
2. Make changes
3. Create pull request
4. Grab a cup of coffee
