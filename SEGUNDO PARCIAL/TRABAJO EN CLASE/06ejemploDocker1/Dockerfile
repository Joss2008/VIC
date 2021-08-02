# imagen base 
FROM node

#copia de los archivos con menos requerimiento
#basada en distribucion de linux en esta se tiene primero la carpeta var 
#y luego en wwww

COPY . /var/www

#luego se ejecuta y para esto se utiliza el siguiente comando seguido de la carpeta de trabajo

WORKDIR /var/www

#este comando es para poner la parte ejecutable y el parametro pero pueden ser varios parametros

ENTRYPOINT ["node", "index.js"]
