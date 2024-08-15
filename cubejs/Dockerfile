FROM node:18

WORKDIR /cube

# Instala dependências do Cube.js
RUN npm install -g @cubejs-backend/cli

# Copia a configuração do Cube.js
COPY . .

# Instala as dependências do projeto
RUN npm install

# Expõe a porta do Cube.js
EXPOSE 4000

CMD ["npm", "start"]
