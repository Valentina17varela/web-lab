# Discord Clone

![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=yellow&color=4b8bbe)
![](https://img.shields.io/badge/Framework-Django-informational?style=flat&logo=django&logoColor=white&color=28BB0E)
![](https://img.shields.io/badge/Code-SQLite-informational?style=flat&logo=sqlite&logoColor=white&color=f29111)
![](https://img.shields.io/badge/Code-HTML-informational?style=flat&logo=html5&color=f06529)
![](https://img.shields.io/badge/Code-CSS-informational?style=flat&logo=css3&color=4b8bbe)

Django application, a messaging service that allows users to communicate through channels.

## Deploy

- Clonar el siguiente repositorio
```
git clone https://github.com/Valentina17varela/Discord_Clone.git
```

- Crear el entorno virtual y activarlo

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

- Instalar las dependencias necesarias
```
pip install -r requirements.txt
```

- Migrar las bases de datos
```
python manage.py makemigrations
python manage.py migrate
```

- Correr aplicacion
```
python manage.py runserver
```
El servidor iniciará en http://127.0.0.1:8000/
<br>
