# Use uma imagem base do Nginx
FROM nginx:alpine

# Copia os arquivos compilados do Angular para o diretório padrão do Nginx
COPY dist/ /usr/share/nginx/html

# Exponha a porta usada pelo Nginx
EXPOSE 80