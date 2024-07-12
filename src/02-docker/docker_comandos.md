# Colocarnos en el Directorio
cd /mnt/c/Users/INGENIERO\ SALINA/OneDrive/0_TRABAJO\ NUEVO/00_CURSOS\ Y\ MATERIAS/16_\ MONGODB/mongo-intro

cd /mnt/c/Users/Ingenieria/OneDrive/0_TRABAJO\ NUEVO/00_CURSOS\ Y\ MATERIAS/16_\ MONGODB/mongo-intro


// En el Shell de Linux correctamente ubicado

# Levantar el Servicio

'''sh
docker compose up -d mongodb

'''

# Checkear el Servicio

'''sh
docker-compose ps

'''

# Para ver todos los contenedores, incluidos los detenidos

docker ps -a

# Iniciar un Contenedor Detenido

docker start <nombre_del_contenedor>

# Crear y Ejecutar un Contenedor

docker run -d --name <nombre_del_contenedor> <nombre_de_la_imagen>



