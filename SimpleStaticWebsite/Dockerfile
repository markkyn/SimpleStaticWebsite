# Use a imagem oficial do Python
FROM python:3.9

# Define o diretório de trabalho
WORKDIR /usr/src/app

# Copia os arquivos do diretório atual para o contêiner
COPY . .

# Expõe a porta que o servidor vai usar
EXPOSE 8000

# Comando para iniciar o servidor HTTP
CMD ["python", "-m", "http.server", "8000"]