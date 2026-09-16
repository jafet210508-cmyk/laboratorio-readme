# Laboratorio README
![Estado](https://img.shields.io/badge/build-passing-brightgreen)

Proyecto de práctica para aprender Markdown avanzado en GitHub.

## Tabla de Contenidos
- [Descripción](#descripción)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estado de funcionalidades](#estado-de-funcionalidades)
- [Arquitectura](#arquitectura)
- [Contribuidores](#contribuidores)

## Descripción
Este repositorio documenta paso a paso mi aprendizaje de Markdown: tablas, listas de tareas, badges y diagramas.

## Instalación
```bash
git clone https://github.com/jafet210508-cmyk/laboratorio-readme.git
cd laboratorio-readme
npm install
## Uso
Para ejecutar el proyecto en entorno local:
```bash
npm start

## Estado de funcionalidades
 
| Función  | Estado      |
|----------|-------------|
| Login    | Listo       |
| Reportes | En progreso |

## Pendientes
 
- [x] Diseño de la base de datos
- [ ] Pruebas unitarias
- [x] Diseño de la base de datos
- [ ] Pruebas unitarias

![Estado](https://img.shields.io/badge/build-passing-brightgreen)

## Arquitectura

mermaid
graph LR
    A[Usuario] --> B[Frontend]
    B --> C[API]
    C --> D[(Base de datos)]