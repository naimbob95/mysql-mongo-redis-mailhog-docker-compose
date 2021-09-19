# Mysql,Mongodb,Redis and Mailhog docker compose file

This is a docker-compose file for with Mysql,Mongodb,Redis and Mailhog for your local development.

# Reminder
Don't use this in your production server!!! This configuration targeted to local development only. I will be not responsible in any of your action using this file. Use this at your own risk!!!

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
  1. Make sure you have install docker in your linux.
```

Mac OS (Tested with apple silicon):
```bash
1. Install Docker Desktop on your Mac OS.
2. For Mac os with Apple silicon Processor it is recommended to use MariaDB 10.5.8
3. Just comment line 4 and uncomment line 5 to use MariaDB.
4. If you want to try and experiment with mysql on apple silicon, just add "platform: linux/x86_64" on top of line 4.
```

![Docker Compose File ](https://user-images.githubusercontent.com/13710927/133922104-d31d834d-a675-4c72-83c3-f81fdae5b17e.png)


# Run Locally

Clone the project

```bash
git clone https://github.com/naimbob95/mysql-mongo-redis-mailhog-dockerfile.git
```



Rename project folder to be more shorter and easier to access (for example dev):
```bash
mv mysql-mongo-redis-mailhog-docker-compose/ dev/ 
```

Go to the project directory

```bash
cd <project-directory>
```

Initialize the container

```bash
docker-compose up -d
```

It should be up and the docker desktop should be showing like this

![Up and Running](https://user-images.githubusercontent.com/13710927/133921630-3b1897b8-cd54-41cb-be18-0022daa3a327.png)



  