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

## 🧭 Navegación

La interfaz de Groove estará organizada en cinco opciones principales:

- **Inicio:** resumen personal y, en futuras versiones, descubrimiento musical.
- **Buscar:** búsqueda de álbumes, EPs, conciertos y ediciones físicas.
- **Añadir:** registro rápido de escuchas, conciertos y elementos físicos.
- **Actividad:** historial cronológico de acciones musicales personales y, posteriormente, sociales.
- **Perfil:** identidad musical, diario de escuchas, conciertos y colección física.

El desarrollo combinará una experiencia de diario musical personal con una futura red social centrada en la música.

Las funcionalidades sociales se incorporarán progresivamente, manteniendo la utilidad individual de la aplicación.

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
- Navegación principal con cinco elementos.
- Acción rápida para registrar experiencias musicales.
- Historial cronológico de actividad personal.
Las versiones posteriores incorporarán personalización, funcionalidades sociales, descubrimiento musical y nuevas integraciones.


## 📚 Documentación

La documentación inicial del proyecto se encuentra disponible en:

- [Objetivos del proyecto](docs/proyecto/objetivos.md)
- [Alcance del MVP — Groove v0.1](docs/proyecto/alcance-mvp.md)
- [Mapa de navegación](docs/diseno/navegacion.md)

La documentación se ampliará progresivamente con el diseño de la interfaz, el modelo de dominio y las decisiones arquitectónicas.


## 👨‍💻 Autor

**Marcelo Díez Domínguez**

Estudiante de Ingeniería Informática del Software — Universidad de Oviedo.

[GitHub](https://github.com/marceloodiezz)