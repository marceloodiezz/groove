# 🎵 Groove

**Groove** es una aplicación web para registrar, valorar y reseñar música, guardar experiencias de conciertos y gestionar colecciones de música física.

Inspirada en plataformas como *Letterboxd*, Groove busca reunir diferentes aspectos de la experiencia musical en una única aplicación, con el objetivo de evolucionar hacia una plataforma social centrada en la música.

## 🎧 Funcionalidades

Groove se organiza en tres bloques principales:

### 🎶 Diario musical

- Buscar álbumes y EPs.
- Registrar álbumes y EPs escuchados.
- Valorar publicaciones mediante un sistema de cinco estrellas.
- Escribir y gestionar reseñas.
- Consultar el historial de escuchas.

### 🎤 Diario de conciertos

- Registrar conciertos a los que se ha asistido.
- Guardar información sobre artistas, fechas, recintos y ubicaciones.
- Valorar conciertos y escribir reseñas.
- Consultar el historial de conciertos.

### 💿 Colección física

- Gestionar colecciones personales de CDs y vinilos.
- Asociar los elementos físicos con álbumes y ediciones.
- Registrar varias copias de una misma publicación.
- Consultar, editar y organizar la colección personal.

## 🛠️ Tecnologías

Las tecnologías previstas para el desarrollo son:

| Área | Tecnologías |
|---|---|
| Frontend | React, TypeScript, Vite |
| Backend | Java, Spring Boot |
| Base de datos | PostgreSQL |
| Persistencia | Spring Data JPA, Hibernate, Flyway |
| Pruebas | JUnit, Mockito, Vitest, Playwright, Testcontainers |
| Infraestructura | Docker, GitHub Actions |
| Diseño | Figma |
| Información musical | MusicBrainz, Cover Art Archive |

La arquitectura seguirá un modelo **cliente-servidor**, con una API REST y un backend organizado como monolito modular.

## 🚧 Estado del proyecto

**En desarrollo — Fase I: Análisis y diseño.**

Groove es un proyecto personal, desarrollado de manera paralela a los estudios universitarios.

El desarrollo seguirá una metodología incremental, priorizando el aprendizaje, la calidad del código y la mantenibilidad.

El primer objetivo será obtener **Groove v0.1 (MVP)**, que incluirá:
- Gestión y autenticación de usuarios.
- Catálogo musical y búsqueda de álbumes y EPs.
- Diario musical con valoraciones y reseñas.
- Registro y valoración de conciertos.
- Gestión de colecciones físicas.
- Perfil personal y resumen de actividad.
- Aplicación web responsive y funcional.
Las versiones posteriores incorporarán personalización, funcionalidades sociales, descubrimiento musical y nuevas integraciones.


## 📚 Documentación

La documentación inicial del proyecto se encuentra disponible en:

- [Objetivos del proyecto](docs/proyecto/objetivos.md)
- [Alcance del MVP — Groove v0.1](docs/proyecto/alcance-mvp.md)

La documentación se ampliará progresivamente con el diseño de la interfaz, el modelo de dominio y las decisiones arquitectónicas.


## 👨‍💻 Autor

**Marcelo Díez Domínguez**

Estudiante de Ingeniería Informática del Software — Universidad de Oviedo.

[GitHub](https://github.com/marceloodiezz)