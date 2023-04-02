# install image
FROM python:alpine

# there will be other folders inside container
# can be my/app ex, will create folder my and app
# docker make a cd and go to this directory
WORKDIR /app

# copia arquivos do computador para o diretorio
# can be . .
COPY . /app

# to install pymongo
RUN pip install -r requirements.txt

# ["executable", "parameter",, ]
# Can be main.py (by the cd)
CMD ["python", "/app/main.py"]