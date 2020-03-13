 CRUD com python usando DJANGO

Faça download cliando em download zip onde mostra a imagem:

>![fg4](https://user-images.githubusercontent.com/49026950/76280713-89be5480-6271-11ea-915a-bd484b91b0b7.png)

Ou clone o projeto com o comando (necessário ter o github instalado em sua máquina):
```
$ git clone https://github.com/feitosajoas/crud-django.git
```
---------------------------------------------------------------
Para início do projeto deve-se criar um ambiente virtual, usei o pipenv para este projeto. Assim instalando o django dentro dele, para não termos problemas futuros.

#### Executar os seguintes comandos para criar o ambiente dentro da pasta do projeto e instalar o django nela:
```
$ cd proj-ecope
$ pipenv install
```
Quando o ambiente virtual estiver pronto instalamos o django:
```
$ pipenv install django
```

#### Com o ambiente virtual todo preparado dentro da pasta do projeto vamos aos comandos que cria o banco de dados:
```
$ python manage.py makemigrations
```
Obtendo sucesso do código anterior, basta apenas criar o banco:
```
$ python manage.py migrate
```

#### Criado o banco de dados, agora vamos rodar o projeto:
```
$ python manage.py runserver
```

#### Imagens do CRUD
>![fg1](https://user-images.githubusercontent.com/49026950/76281022-9a22ff00-6272-11ea-8fad-e6f47eda2b11.png)

>![fg2 2](https://user-images.githubusercontent.com/49026950/76281614-5af5ad80-6274-11ea-94df-1423f17221b1.png)

>![fg3 1](https://user-images.githubusercontent.com/49026950/76281551-22ee6a80-6274-11ea-85bf-8adf6e9b22a5.png)
