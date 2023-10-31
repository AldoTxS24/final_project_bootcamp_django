# Proyecto Aldo Texis - Cine

1. Crea un ambiente virtual:
```
python3 -m venv env
```
2. Activa el ambiente virtual:
```
# Activación en Unix
source env/bin/activate
```
```
# Activación en Windows
env\Scripts\activate
```

3. Instala las dependencias del archivo requirements.txt

```
pip install -r requirements.txt
```

4. Genera las migraciones y ejeculatas:
```
python manage.py makemigrations
python manage.py migrate
```
5. Crea un super usuario:
```
python manage.py createsuperuser
```
6. Corre la aplicación:
```
python manage.py runserver
```

7. Para lanzar abrir el endpoint para dar de alta un usuario hay que abrir el link:
```
http://143.244.180.12:8000/usuarios/signup
```

8. TEST
