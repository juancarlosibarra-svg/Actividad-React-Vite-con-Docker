# Catálogo de Videojuegos - Web

Aplicación frontend construida con React y Vite, contenedorizada con Docker.

## Requisitos

- Node.js 20+ (para desarrollo local)
- Docker

## Desarrollo local

```bash
npm install
npm run dev
```

La aplicación queda disponible en `http://localhost:5173`.

## Construir y ejecutar con Docker

```bash
docker build -t catalogo-videojuegos-web .
docker run -d -p 8080:80 --name catalogo-videojuegos-web catalogo-videojuegos-web
```

La aplicación queda disponible en `http://192.168.1.80:5173/`.

## Detener el contenedor

```bash
docker stop catalogo-videojuegos-web
docker rm catalogo-videojuegos-web
```

