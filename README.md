# SQLi Wordpress Challenge

This project is designed as a challenge for a CTF.
The docker container contains following exploit:
https://www.exploit-db.com/exploits/40804/

## Requirements
1. Docker installed
2. Docker Compose installed

## Quick-Start
1. Clone Git Repository and switch to the Repository-Folder.
2. `docker-compose up`

To shut the challenge down:  `docker-compose down`

## Custom Flag
The standard flag / solution is saved in the .env file and is 'root'.

## Troubleshooting
### Flag wrong
Connect to the MySQL-Container and test the Flag.
If the flag is not set correct try to delete containers with:
```
docker-compose down
```

# Task
Try to exploit the website and submit the password of the 'root' user.
