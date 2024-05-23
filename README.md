# Products Microservice 



## Dev

1. Clonar el repositorio
2. Instalar las dependencias
2. Crear el archivo `.env` basado en el archivo `.env.template`
4. Ejecutar migracion de Prisma `npx prisma migrate dev`
5. Levantar el servicor de NATS
```
docker run -d --name nats-sever -p 4222:4222 -p 8222:8222 nats
```
6. Levantar el proyecto con `npm run start:dev` 