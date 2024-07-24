# Usa una imagen base
FROM node:16

# Establece el directorio de trabajo
WORKDIR /app

# Copia package.json e instala dependencias
COPY package*.json ./
RUN npm install

# Copia el resto del código
COPY . .

# Expone el puerto en el que la app escuchará
EXPOSE 3002

# Comando para ejecutar la aplicación
CMD ["node", "index.js"]
