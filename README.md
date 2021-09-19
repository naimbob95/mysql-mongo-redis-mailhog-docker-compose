
# Mysql,Mongodb,Redis and Mailhog docker compose file

This is a docker-compose file for with Mysql,Mongodb,Redis and Mailhog for your local development.

# Prerequisites

Windows (Tested on Windows 10):
```bash
  1. Install and configure WSL 2 on your pc.
  2. Install Ubuntu 20.04 on your WSL 2.
  3. Install and setup Docker Desktop on your pc.
  4. Make sure the docker desktop use WSL 2 based engine (can check in Settings>General).
```

Linux (Tested on Ubuntu Desktop):
```bash
  1. Make sure you have install ubuntu in your desktop.
```

Mac OS (Tested with apple silicon):
```bash
1. Install Docker Desktop on your Mac OS.
2. For Mac os with Apple silicon Processor it is recommended to use MariaDB 10.5.8


# Mysql,Mongodb,Redis and Mailhog docker compose file

This is a docker-compose file for with Mysql,Mongodb,Redis and Mailhog for your local development.

# Prerequisites

Windows (Tested on Windows 10):
```bash
  1. Install and configure WSL 2 on your pc.
  2. Install Ubuntu 20.04 on your WSL 2.
  3. Install and setup Docker Desktop on your pc.
  4. Make sure the docker desktop use WSL 2 based engine (can check in Settings>General).
```

Linux (Tested on Ubuntu Desktop):
```bash
  1. Make sure you have install ubuntu in your desktop.
```

Mac OS (Tested with apple silicon):
```bash
1. Install Docker Desktop on your Mac OS.
2. For Mac os with Apple silicon Processor it is recommended to use MariaDB 10.5.8
3. Just comment line 4 and uncomment line 5 to use MariaDB.
4. If you want to try and experiment with mysql on apple silicon, just add "platform: linux/x86_64" on top of line 4.
![alt text](https://imgur.com/a/89GPZoT")
```




## Run Locally

Clone the project

```bash
  git clone https://github.com/naimbob95/mysql-mongo-redis-mailhog-dockerfile.git
```

Go to the project directory

```bash
  cd <project-directory
```

Initialize the container

```bash
  docker-compose up -d
```

It should be up and the docker desktop should be showing like this

![alt text]("ss1.png")


  