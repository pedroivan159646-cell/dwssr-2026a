<p align="center">
<img src="./.github/assets/image.png" alt="logo">
</p>
<h1> Desarrollo web SSR</h1>
<p>repositorio de la materia de desarrollo web  SSR (server side rendering)</P>
<h2>Contenido</h2>
- Ramas de trabajo.
-Proyecto eje de la materia
<h2> Ramas del proyecto</h2>

- `dev`:Rama de desarrollo.
- `dev`: Rama principal.

## Convenciones de commits

|Código     |Descripción      |
|-----------|-----------------|
|feat:      |Nueva funcionalidad
|fix:       |Corrección de errores
|docs:      |Cambios en la documentación
|style:     |Cambio de aspecto visual
|refactor:  |Refactorización de código
|perf:      |Mejoras de rendimiento
|test:      |Cambios de los test
|chore: |Cambios en dependencias
|ci|Cambios en el CI/CD
|Revert|Reversión de commits
 
 **ejemplo:**
 >feat: agrega automatización de usuarios

 # Autor
[Cortes González pedro iván]()

## Node 
- [Node](./.github/assets/doc/node.md) es un entorno de ejecución multiplataforma de código abierto y gratis.
Dentro de los frameworks para crear servidores web para Node tenemos:
- [Fastify](https://fastify.dev/)
- [AdonisJs](https://adonisjs.com/)
- [Nestjs](https://nestjs.com/)
- [Koa](https://koajs.com/)
- [ExpressJs](https://expressjs.com/)

# 🟣 ExpressJs
Express es un __framework__ para Node, mínimo, 
flexible no es impositivo tanto en el flujo 
de trabajo como en la arquitectura del proyecto.

El presente proyecto está desarrollado en ExpressJs

# 📦 ESM
Los ECMAScript Modules (ESM) representan el estándar nativo 
para organizar y modularizar código de Javascript.
El express-generator genera un proyecto usando el antiguo estándar llamado __CommonJS__ 
que usa las sentencias require el nuevo estándar llamado usa export/import.

Migrar a ESM ofrece las siguientes ventajas:
- Sintaxis moderna y consistente
- Mejor análisis estático
- Importaciones asíncronas con import()
- Es el futuro del ecosistema.
