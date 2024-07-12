
cd /mnt/c/Users/INGENIERO\ SALINA/OneDrive/0_TRABAJO\ NUEVO/00_CURSOS\ Y\ MATERIAS/16_\ MONGODB/mongo-intro

# Ejecutar servicio mongodb

docker-compose exec mongodb bash

# Conectar con mongosh

mongosh "URL DE MONGO COMPASS o la URL de ATLAS"
mongosh "mongodb://admin:tooR@localhost:27017/?tls=false"

show dbs
show collections


use("ger_store")
db.products.find()

