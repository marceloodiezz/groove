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

### 🎤 Conciertos

- Registrar conciertos a los que se ha asistido.
- Guardar información sobre artistas, fechas, recintos y ubicaciones.
- Valorar conciertos y escribir reseñas.
- Consultar las asistencias dentro del Diario musical, utilizando el filtro Conciertos.

El Diario reunirá las escuchas y las experiencias de conciertos en un historial cronológico unificado.

### 💿 Colección física

- Gestionar colecciones personales de CDs y vinilos.
- Asociar los elementos físicos con álbumes y ediciones.
- Registrar varias copias de una misma publicación.
- Consultar, editar y organizar la colección personal.

## 🧭 Navegación

Groove dispondrá de dos zonas:

- **Zona pública:** Bienvenida, Registro e Inicio de sesión.
- **Zona privada:** funcionalidades disponibles para usuarios autenticados.

La navegación privada estará formada por cinco elementos principales:

1. **Inicio:** resumen visual de la actividad musical personal.
2. **Buscar:** consulta de álbumes, EPs, conciertos y ediciones.
3. **Añadir:** acción rápida para registrar escuchas, conciertos y copias físicas.
4. **Actividad:** historial cronológico de acciones musicales.
5. **Perfil:** identidad personal y acceso al Diario, Colección y funcionalidades asociadas.

### Perfil personal

La sección Perfil se organizará mediante cuatro pestañas:

- **Perfil:** información personal, contadores y actividad reciente.
- **Diario:** historial de escuchas y conciertos, con filtros por tipo de experiencia.
- **Colección:** biblioteca de CDs, vinilos y otras copias físicas.
- **ListenList:** álbumes y EPs pendientes de escuchar, prevista para la v0.2.

La aplicación ofrecerá una navegación adaptable:

- Barra inferior en móvil.
- Menú lateral en escritorio.
- Acciones rápidas mediante paneles y diálogos contextuales.

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
| Diseño | draw.io, Figma |
| Información musical | MusicBrainz, Cover Art Archive |

La arquitectura seguirá un modelo **cliente-servidor**, con una API REST y un backend organizado como monolito modular.

## 🚧 Estado del proyecto

**En desarrollo — Fase I: Análisis y diseño.**

Groove es un proyecto personal, desarrollado de manera paralela a los estudios universitarios.

El desarrollo seguirá una metodología incremental, priorizando el aprendizaje, la calidad del código y la mantenibilidad.

### Primera versión — Groove v0.1 (MVP)

El primer objetivo será obtener una aplicación funcional que incluya:

- Gestión y autenticación de usuarios.
- Catálogo musical y búsqueda.
- Diario unificado de escuchas y conciertos.
- Valoraciones y reseñas.
- Gestión de colecciones físicas.
- Perfil personal y resumen de actividad.
- Historial cronológico de actividad personal.
- Navegación responsive.
- Acción rápida para registrar experiencias.
- Fichas de álbumes, conciertos y elementos físicos.

### Evolución prevista

- **v0.2 — Personalización:** favoritos, ListenList, calendario y mejoras del perfil.
- **v0.3 — Red social:** seguimiento, perfiles públicos y actividad social.
- **v0.4 — Descubrimiento:** recomendaciones y exploración musical.
- **v1.0 — Plataforma ampliada:** nuevas integraciones y funcionalidades.

## 📚 Documentación

### Proyecto

- [Objetivos del proyecto](docs/proyecto/objetivos.md)
- [Alcance del MVP — Groove v0.1](docs/proyecto/alcance-mvp.md)

### Diseño

- [Estructura de navegación](docs/diseno/navegacion.md)
- [Inventario de pantallas](docs/diseno/inventario-pantallas.md)
- [Bocetos de interfaz](docs/diseno/bocetos.md)

Los bocetos originales y sus exportaciones se encuentran organizados en `docs/diseno/bocetos/`.

La documentación se ampliará progresivamente con los prototipos de Figma, el modelo de dominio y las decisiones arquitectónicas.

## 👨‍💻 Autor

**Marcelo Díez Domínguez**

Estudiante de Ingeniería Informática del Software — Universidad de Oviedo.

[GitHub](https://github.com/marceloodiezz)