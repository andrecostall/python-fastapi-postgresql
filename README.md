# python-fastapi-postgresql

# Criar e ativar um ambiente virtual
*  $ cd projeto
*  $ python3 -m venv .venv
*  $ source .venv/bin/activate

# Instalação das bibliotecas necessárias utilizando o PIP.
*  pip install fastapi
*  pip install uvicorn[standard]
*  pip install sqlalchemy
*  pip install psycopg2-binary

# Executar a nossa aplicação, comando no terminal
* uvicorn main:app --reload
