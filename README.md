# libpythonpro

![example workflow](https://github.com/maldonadopereira/libpythonpro/actions/workflows/django.yml)

Projeto para exemplificar a construção de projetos Python, utilizando o ambiente virtual Pipenv e
aplicando lint com Flake8 e Integração contínua.


## Instalação

1. clonar o repositório em algum diretório escolhido:
```bash
git clone https://github.com/maldonadopereira/libpythonpro.git
```

2. Criar uma venv, no exemplo a seguir será utilizado o pipenv:
```bash
pipenv install
pipenv shell
```

3. Instalar as dependências:
```bash 
pipenv sync 
```

## Conferir quaidade do código (Lint)


```bash
flake8
```
