# Projeto Realizado durante o Semestre 2020/2 UNB

- Instalação do projeto pode ser feita seguindo os passos a seguir:
1) Verificar se possui o python instalado.
2) Após verificar se possuir o python instalado, vamos para a pasta do projeto e executamos o comando:
- python manage.py runserver
3) Pronto projeto estará rodando no localhost:8000.

Instalar em servidor de produção:
```
sudo apt-get update

sudo apt-get install python3  python3-pip

git clone https://github.com/Benedito-Medeiros-Neto-UnB/WikiJour-Data.git

cd WikiJour-Data

pip3 install -r requirements.txt

vi myproject/settings.py 
ALLOWED_HOSTS = ['ip_servidor']

python3 ./manage.py runserver 0.0.0.0:8000
```
