# Products-ms

## Descripción

Este es un proyecto de microservicio para productos.

## Scripts Disponibles

- `build`: Compila el proyecto.
- `format`: Formatea los archivos TypeScript.
- `start`: Inicia el proyecto.
- `start:dev`: Inicia el proyecto en modo desarrollo.
- `start:debug`: Inicia el proyecto en modo debug.
- `start:prod`: Inicia el proyecto en producción.
- `lint`: Ejecuta ESLint para linting.
- `test`: Ejecuta pruebas unitarias.
- `test:watch`: Ejecuta pruebas en modo watch.
- `test:cov`: Genera reporte de cobertura de pruebas.
- `test:e2e`: Ejecuta pruebas end-to-end.

## Dependencias Principales

- `@nestjs/common`: ^10.0.0
- `@nestjs/core`: ^10.0.0
- `class-transformer`: ^0.5.1
- `class-validator`: ^0.14.1
- `rxjs`: ^7.8.1
- `typescript`: ^5.1.3

## Dependencias de Desarrollo

- `@nestjs/cli`: ^10.0.0
- `@nestjs/testing`: ^10.0.0
- `eslint`: ^8.42.0
- `jest`: ^29.5.0
- `prettier`: ^3.0.0
- `ts-jest`: ^29.1.0
- `ts-node`: ^10.9.1
- `typescript`: ^5.1.3

## Estructura de Pruebas

- Archivos de pruebas en formato `.spec.ts`.
- Configuración de Jest en `jest` en el `package.json`.

## Otros Detalles

- Proyecto basado en NestJS.
- Utiliza ESLint para linting.
- Configuración de Jest para pruebas.

## Dev

1. Clonar el repositorio
2. Instalar dependencias
3. Crear un archivo `.env` basado en el `.env.template`.
4. Ejecutar migracion de prisma `npx prisma migrate dev`
5. Ejecutar el proyecto `npm run start:dev`
