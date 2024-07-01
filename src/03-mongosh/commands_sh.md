# Ejecutar servicio mongodb

docker-compose exec mongodb bash

# Conectar con mongosh

mongosh ""

show dbs
show collections


use("ger_store")
db.products.find()
