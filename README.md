# Python Django  - Como rodar

> Usando docker compose: 

docker compose build

docker compose up

> Usando docker build:

docker build -t nomedainstancia .

docker run -p 8000:8000 -v $(pwd):/app nomedainstancia

