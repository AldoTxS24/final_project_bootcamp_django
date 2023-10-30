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
python manage.py makemigrations --settings=settings.local
python manage.py migrate --settings=settings.local
```
5. Crea un super usuario:
```
python manage.py createsuperuser --settings=settings.local
```
6. Corre la aplicación:
```
python manage.py runserver --settings=settings.local
```

7. Para lanzar abrir el endpoint para dar de alta un usuario hay que abrir el link:
```
http://127.0.0.1:8000/usuarios/signup
```

