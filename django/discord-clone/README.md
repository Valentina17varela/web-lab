# Discord Clone

![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=yellow&color=4b8bbe)
![](https://img.shields.io/badge/Framework-Django-informational?style=flat&logo=django&logoColor=white&color=28BB0E)
![](https://img.shields.io/badge/Code-SQLite-informational?style=flat&logo=sqlite&logoColor=white&color=f29111)
![](https://img.shields.io/badge/Code-HTML-informational?style=flat&logo=html5&color=f06529)
![](https://img.shields.io/badge/Code-CSS-informational?style=flat&logo=css3&color=4b8bbe)

Django application, a messaging service that allows users to communicate through channels.

<div align="center">
  <img src="https://github.com/Valentina17varela/Discord_Clone/blob/main/static/images/preview.PNG" width="900"/>
  <img src="https://github.com/Valentina17varela/Discord_Clone/blob/main/static/images/room.PNG" width="900"/>
  <img src="https://github.com/Valentina17varela/Discord_Clone/blob/main/static/images/register.PNG" width="900"/>
</div>

## 🚀 Functionalities

- Register / Login : You must create an account to interact with the community.
- Edit profile: You can edit your personal information, as well as save a profile picture.
- Create rooms: You can create your own rooms to share information about whatever you like, other users will be able to join these rooms and exchange information.
- Search: You can search for key terms within the rooms and posts.

## ⚙ Deploy

- Clone the following repository
```
git clone https://github.com/Valentina17varela/Discord_Clone.git
```

- Create the virtual environment and activate it

  - Windows:
  ```
  pip install virtualenv
  py -m venv env
  env\scripts\activate
  ```
  - Unix/macOS:
  ```
  pip install virtualenv
  python3 -m venv env
  source env/bin/activate
  ```

- Install the necessary dependencies
```
pip install -r requirements.txt
```

- Migrate databases
```
python manage.py makemigrations
python manage.py migrate
```

- Run application
```
python manage.py runserver
```
Server will start in http://127.0.0.1:8000/
<br>
