[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19274834&assignment_repo_type=AssignmentRepo)



# Exercico Vital
Tutorial Django


# Criar a base de dados sqlite3 padrão do django, mas podemos utilizar qualquer SGBD
```bash
python manage.py migrate
```
# Rodar o servidor web do Django
```bash
python manage.py runserver
```


# Efetivar alterações no banco de dados
```bash
python manage.py makemigrations
# E
python manage.py migrate
```

# Criando a venv e ativando
```bash
python -m venv venv
# depois
.\venv\Scripts\activate
# Opcional instalar os requirimentos
pip install -r requirements/r.txt
# Opcional salvar os requirimentos
pip freeze > requirements/r.txt
```
