FROM nginx:latest

# Copier ton nginx.conf dans l'image
COPY nginx.conf /etc/nginx/nginx.conf

# Si tu veux créer un utilisateur spécifique dans le container (optionnel)
RUN adduser --system --no-create-home myuser

# Lancer nginx en mode foreground
CMD ["nginx", "-g", "daemon off;"]
