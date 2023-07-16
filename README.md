# Code_Warriors
A repository for the students who are involved in a web-app project.


<div align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" width="100"/>
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/website-blue?style=for-the-badge&logo=About.me&logoColor=white" width="100"/>
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" width="100"/>
  </a>
</div>


# What is this project?
<span><img src="https://img.shields.io/badge/figma-F24E1E?style=flat&logo=figma&logoColor=gray" /></span>
<span><img src="https://img.shields.io/badge/html5-E34F26?style=flat&logo=html5&logoColor=white" /></span>
<span><img src="https://img.shields.io/badge/css3-1572B6?style=flat&logo=css3&logoColor=green" /></span>
<span><img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat&logo=javascript&logoColor=orange" /></span>
<span><img src="https://img.shields.io/badge/react-61DAFB?style=flat&logo=react&logoColor=orange" /></span>
<span><img src="https://img.shields.io/badge/python-3776AB?style=flat&logo=python&logoColor=yellow" /></span>
<span><img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=blue" /></span>
<span><img src="https://img.shields.io/badge/Docker-2CA5E0?style=flat&logo=docker&logoColor=white" /></span>
<span><img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white" /></span>

# How to use?

<strong>If you want to get notified about the future changes Follow this github account.</strong>

First clone the project.

```bash
git clone https://github.com/AlonePyWarrior/Code_Warriors.git
```

Then make sure Docker is running.
* If you are on windows click on the Docker Desktop icon and wait for about a minute.

Then in the project directory run this command:

```bash
docker-compose up --build
```

It will create two containers:
One for Django and one for PostgreSql as the database for the project.
All the required packages will be installed.

### Install a new package.
* Attention:
If you want to install a package for django project you should run this command:

```bash
docker-compose exec web pip install <package-name>
``` 

Don't forget to add the new package to requirements.txt for further use:
```bash
docker-compose exec web pip freeze > requirements.txt
```
