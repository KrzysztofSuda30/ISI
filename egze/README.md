I. Git
Utworzenie nowej gałęzi i merge do bieżącej


git checkout main
git pull origin main
git checkout -b nowa
touch nowy_plik.txt
git add nowy_plik.txt
git commit -m "Dodano nowy plik"
git checkout main
git merge nowa
Pull request

Utwórz nowe repozytorium na GitHub.
Utwórz nową gałąź lokalnie, wykonaj zmiany i wypchnij do zdalnego repozytorium:

git checkout -b nowa-feature
touch feature.txt
git add feature.txt
git commit -m "Dodano plik feature.txt"
git push origin nowa-feature
Na GitHubie utwórz pull request z gałęzi nowa-feature do main.
Różnica między git fetch a git pull

git fetch pobiera zmiany ze zdalnego repozytorium, ale nie łączy ich z lokalnym.
git pull pobiera zmiany i od razu je łączy z bieżącą gałęzią.

git fetch origin
git diff origin/main
git pull origin main
Działanie git stash

Przykład:

git stash
git stash list
git stash apply
Działanie git rebase vs git merge

git merge łączy dwie gałęzie, zachowując historię commitów.
git rebase przenosi zmiany z jednej gałęzi na drugą, tworząc liniową historię.
Rysunek:


git merge:
A---B---C main
 \     /
  D---E nowa

git rebase:
A---B---C---D'---E' main
II. Bazy danych
Dodanie rekordu do bazy danych (Python + SQLite)


import sqlite3

conn = sqlite3.connect('example.db')
cursor = conn.cursor()
cursor.execute("INSERT INTO users (name, age) VALUES ('Alice', 30)")
conn.commit()
conn.close()
Różne typy JOIN (SQL)


SELECT * FROM orders
INNER JOIN customers ON orders.customer_id = customers.id;

SELECT * FROM orders
LEFT JOIN customers ON orders.customer_id = customers.id;

SELECT * FROM orders
RIGHT JOIN customers ON orders.customer_id = customers.id;
Logowanie do PostgreSQL w kontenerze Dockerowym


docker exec -it my_postgres_container psql -U postgres -d mydatabase
SELECT * FROM mytable;
Różnice między SQLite a PostgreSQL

SQLite: lekka, wbudowana, świetna do prototypowania i małych projektów.
PostgreSQL: zaawansowana, obsługuje bardziej złożone operacje i skalowalne aplikacje.
Przykładowe zapytania SQL


SELECT * FROM users WHERE age > 25;
SELECT * FROM users WHERE name LIKE 'A%';
SELECT COUNT(*) FROM users;
SELECT age, COUNT(*) FROM users GROUP BY age;
SELECT age, COUNT(*) FROM users GROUP BY age HAVING COUNT(*) > 1;
III. Aplikacja wg wzorca projektowego MVC
ORM na przykładzie Django


# models.py
from django.db import models

class Person(models.Model):
    name = models.CharField(max_length=100)
    age = models.IntegerField()
Wzorzec MVC w Django

Model: models.py
View: views.py
Controller: urls.py
Dodanie nowego URL, który wyświetla imię i nazwisko


# urls.py
from django.urls import path
from . import views

urlpatterns = [
    path('imie/', views.show_name),
]

# views.py
from django.http import HttpResponse

def show_name(request):
    return HttpResponse("Jan Kowalski")
Dodanie nowego URL z formularzem dodającym dwie liczby


# urls.py
urlpatterns += [
    path('dodaj/', views.add_numbers),
]

# views.py
from django.shortcuts import render

def add_numbers(request):
    if request.method == 'POST':
        num1 = int(request.POST.get('num1'))
        num2 = int(request.POST.get('num2'))
        result = num1 + num2
        return HttpResponse(f'Wynik: {result}')
    return render(request, 'add_form.html')

# add_form.html
<form method="post">
    {% csrf_token %}
    <input type="number" name="num1" required>
    <input type="number" name="num2" required>
    <button type="submit">Dodaj</button>
</form>
Dodanie nowego URL z wyświetleniem zdjęć z API


# urls.py
urlpatterns += [
    path('photos/', views.show_photos),
]

# views.py
import requests
from django.shortcuts import render

def show_photos(request):
    response = requests.get('https://jsonplaceholder.typicode.com/photos')
    photos = response.json()[:4]
    return render(request, 'photos.html', {'photos': photos})

# photos.html
{% for photo in photos %}
    <img src="{{ photo.url }}" alt="{{ photo.title }}">
{% endfor %}
IV. Docker
Plik Dockerfile


FROM python:3.9-slim
WORKDIR /app
COPY ./code /app/code
CMD ["python", "/app/code/script.py"]
Uruchomienie skryptu w kontenerze

docker build -t myapp .
docker run myapp
Kopiowanie plików między hostem a kontenerem

Z hosta do kontenera


docker cp host_file.txt my_container:/container_path/
Z kontenera do hosta


docker cp my_container:/container_file.txt host_path/
ENTRYPOINT i CMD


ENTRYPOINT ["python"]
CMD ["app.py"]
ADD i COPY oraz WORKDIR


FROM python:3.9-slim
WORKDIR /app
COPY . /app
Docker Compose


version: '3'
services:
  web:
    build: .
    ports:
      - "8000:8000"
    volumes:
      - .:/app
Uruchomienie Docker Compose

docker-compose up
Komendy docker inspect i docker logs

docker inspect


docker inspect my_container
docker logs


docker logs my_container
Sieci w Dockerze

Przykład sieci w Docker Compose
version: '3'
services:
  web:
    build: .
    networks:
      - mynetwork
  db:
    image: postgres
    networks:
      - mynetwork
networks:
  mynetwork:
V. Programowanie
Klasa Kalkulator

class Kalkulator:
    def dodaj(self, a, b):
        return a + b

    def odejmij(self, a, b):
        return a - b

    def mnoz(self, a, b):
        return a * b

    def dziel(self, a, b):
        if b != 0:
            return a / b
        else:
            return "Nie można dzielić przez zero"

kalk = Kalkulator()
print(kalk.dodaj(2, 3))
Pobieranie danych JSON z API

import requests
import json

response = requests.get('https://jsonplaceholder.typicode.com/photos')
data = response.json()

with open('photos.txt', 'w') as file:
    json.dump(data, file)
Odczyt danych z pliku tekstowego

with open('photos.txt', 'r') as file:
    data = file.read()
print(data)
Dziedziczenie w programowaniu obiektowym

class Person:
    def __init__(self, name, surname):
        self.name = name
       
