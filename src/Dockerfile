# Use imagem oficial do Node.js como base
FROM node:20.11.0

# Diretório de trabalho dentro do container
WORKDIR /app

# Copia os arquivos de dependências
COPY package*.json ./

# Instala as dependências
RUN npm install

# Copia o restante da aplicação
COPY . .

# Expõe a porta (ajuste conforme sua aplicação)
EXPOSE 8080

# Comando para iniciar a aplicação
CMD ["node", "server.js"]