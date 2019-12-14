`Utilizando o banco de dados postgres e o gerenciador adminer, podemos gerenciar o banco acessando:
http://localhost:8080/`

## ---- Postgres
sudo docker run \
    --name postgres \
    -e POSTGRES_USER=vsantos93 \
    -e POSTGRES_PASSWORD=swordfish \
    -e POSTGRES_DB=teste \
    -p 5432:5432 \
    -d \
    postgres

## ---- Adminer
sudo docker run \
    --name adminer \
    -p 8080:8080 \
    --link postgres:postgres \
    -d \
    adminer

 