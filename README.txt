
#creacion imagen
docker build -t dashbi07:v1 .

#Ejecucion de la imagen
docker run -p 8050:8050 dashbi07:v1


