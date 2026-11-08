# Práctica 6: Servidor web con Nginx y Docker Compose

Servidor web Nginx corriendo de forma local con Docker Compose. El contenido de la carpeta `src` se monta como volumen en `/usr/share/nginx/html`.

## Cómo ejecutarlo

```bash
docker compose up -d
```

Luego abre en el navegador: http://localhost:8090

Para detenerlo:

```bash
docker compose down
```
