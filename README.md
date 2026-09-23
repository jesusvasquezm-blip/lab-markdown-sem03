# Mi Proyecto Integrador
![build](https://img.shields.io/badge/build-passing-brightgreen) ![license](https://img.shields.io/badge/license-MIT-blue) ![version](https://img.shields.io/badge/version-1.0.0-orange)

Este proyecto es una aplicación desarrollada para el curso de Diseño de Interfaces de Programación Avanzado.

## Tabla de contenidos
- [Instalación](#instalación)
- [Uso](#uso)
- [Arquitectura](#arquitectura)
- [Contribuidores](#contribuidores)


## Tecnologías

| Tecnología | Versión | Propósito          |
| ---------- | ------- | ------------------ |
| Node.js    | 18.x    | Servidor backend   |
| React      | 18.x    | Interfaz de usuario|
| MongoDB    | 6.x     | Base de datos      |

## Estado del proyecto

- [x] Autenticación de usuarios
- [x] CRUD de tareas
- [ ] Notificaciones en tiempo real
- [ ] Despliegue en producción

## Arquitectura

```mermaid
flowchart LR
Cliente -->|HTTPS| API
API -->|SQL| BaseDeDatos
API -->|JWT| ServicioAuth
```
## Capturas

![Vista principal](assets/captura-principal.webp)

## Contribuidores

- [@VASQUEZ](https://github.com/VASQUEZ) — Desarrollo y documentación