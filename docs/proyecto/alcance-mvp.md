# Alcance del MVP — Groove v0.1

## 1. Introducción

Este documento establece el alcance funcional de la primera versión de Groove, denominada **v0.1 — MVP (Minimum Viable Product)**.

Groove es una aplicación web destinada a registrar, valorar y reseñar álbumes y EPs, conservar experiencias de conciertos y gestionar colecciones físicas de música.

El objetivo del MVP es desarrollar una primera versión funcional, estable y utilizable, que reúna las funcionalidades esenciales de organización musical personal.

Las funcionalidades sociales y las características avanzadas se incorporarán progresivamente en versiones posteriores.

## 2. Objetivo del MVP

Desarrollar y publicar una aplicación web que permita a un usuario registrado gestionar su actividad musical personal mediante tres áreas principales:

- **Diario musical:** registro de escuchas, valoraciones y reseñas de álbumes y EPs.
- **Diario de conciertos:** registro, valoración y reseña de conciertos a los que se haya asistido.
- **Colección física:** organización de CDs, vinilos y sus correspondientes ediciones y copias.

Estas funcionalidades estarán centralizadas en un perfil personal.

## 3. Funcionalidades incluidas

### 3.1. Gestión de usuarios

El sistema permitirá:

- Registrar usuarios mediante nombre de usuario, correo electrónico y contraseña.
- Validar los datos y evitar nombres de usuario y correos duplicados.
- Iniciar y cerrar sesión de forma segura.
- Mantener la sesión autenticada entre accesos desde un mismo dispositivo o navegador, mientras continúe siendo válida.
- Redirigir al usuario autenticado a la página principal.
- Consultar un perfil personal.
- Modificar el nombre visible, la descripción y otros datos permitidos.
- Proteger los recursos personales frente a accesos no autorizados.

### 3.2. Catálogo musical

El sistema permitirá:

- Buscar álbumes y EPs por nombre o artista.
- Buscar conciertos registrados en la aplicación mediante sus datos disponibles, como artista, fecha o ubicación.
- Buscar y consultar ediciones físicas registradas o identificadas en el catálogo de Groove.
- Consultar resultados con título, artista, portada y año, cuando estén disponibles.
- Acceder a la ficha de una publicación musical.
- Identificar de forma estable artistas y álbumes.
- Asociar un álbum con varios artistas.
- Diferenciar álbumes y EPs.
- Conservar localmente la información necesaria para relacionar las publicaciones con los registros personales.
- Gestionar errores y respuestas incompletas de los servicios musicales externos.

El catálogo se alimentará de fuentes externas, principalmente MusicBrainz y Cover Art Archive.

La búsqueda de conciertos y ediciones físicas durante el MVP se limitará a la información disponible en la aplicación.

Los conciertos podrán registrarse manualmente y las ediciones físicas podrán incorporarse aunque no se conozcan todos sus datos.

La integración con catálogos externos especializados en conciertos y ediciones físicas podrá incorporarse en versiones posteriores.

### 3.3. Diario musical

El usuario podrá:

- Marcar álbumes y EPs como escuchados.
- Registrar una fecha de escucha.
- Valorar publicaciones mediante estrellas de 0,5 a 5, en incrementos de media estrella.
- Registrar escuchas sin necesidad de asignar una valoración.
- Escribir reseñas personales.
- Modificar y eliminar sus propias valoraciones y reseñas.
- Consultar su historial musical cronológico.
- Consultar su valoración personal desde la ficha del álbum.

Cada usuario podrá mantener una valoración general activa por álbum.

El modelo de datos deberá permitir incorporar escuchas repetidas en futuras versiones, sin duplicar las valoraciones generales.

### 3.4. Diario de conciertos

El sistema permitirá:

- Registrar manualmente conciertos a los que se haya asistido.
- Guardar el artista principal, la fecha, el recinto y la ciudad.
- Valorar conciertos mediante el sistema de estrellas de Groove.
- Escribir reseñas de las experiencias.
- Consultar el historial de conciertos.
- Editar y eliminar registros propios.

No será obligatorio escribir una reseña ni asignar una puntuación para registrar un concierto.

### 3.5. Colección física

El usuario podrá:

- Añadir CDs y vinilos a una colección personal.
- Asociar cada elemento con un álbum o EP.
- Identificar ediciones concretas cuando exista información disponible.
- Registrar objetos cuya edición exacta se desconozca.
- Mantener varias copias de un mismo álbum o edición.
- Consultar la colección mediante listados y cuadrículas de portadas.
- Modificar y eliminar elementos de la colección.

El sistema distinguirá entre el álbum, su edición comercial y la copia física que pertenece al usuario.


### 3.6. Perfil personal

El sistema proporcionará:

- Un perfil con la información básica del usuario.
- Un resumen del número de álbumes registrados, conciertos y elementos físicos.
- Una sección de actividad reciente.
- Acceso al diario musical y al historial de escuchas.
- Acceso al historial de conciertos y experiencias musicales.
- Acceso a la colección física personal.
- Acceso a los ajustes y a la edición de la información de cuenta.

El perfil constituirá el espacio central de la identidad musical del usuario.

En versiones posteriores incorporará álbumes favoritos, ListenList, estadísticas avanzadas y funcionalidades sociales.


### 3.7. Navegación y actividad personal

Groove estará organizado en dos zonas principales:

- **Zona pública:** Bienvenida, Registro e Inicio de sesión.
- **Zona privada:** funcionalidades disponibles para usuarios autenticados.

La navegación principal de la zona privada estará formada por cinco elementos:

1. **Inicio:** página principal con un resumen de la actividad musical personal y accesos a las funcionalidades.
2. **Buscar:** búsqueda y consulta de contenido musical.
3. **Añadir:** acción rápida para registrar escuchas, conciertos y elementos físicos.
4. **Actividad:** historial cronológico de las acciones musicales del usuario.
5. **Perfil:** información personal, diario musical, conciertos y colección física.

La acción Añadir permitirá iniciar las operaciones correspondientes desde un único punto, sin impedir que puedan realizarse también desde las fichas de contenido.

La sección Actividad mostrará inicialmente los registros personales del usuario y mantendrá esta información privada.

En versiones posteriores podrá incorporar un historial de actividad de usuarios seguidos.

La navegación será adaptable a dispositivos móviles y de escritorio.

La estructura detallada se encuentra documentada en el [Mapa de navegación](../diseno/navegacion.md).

### 3.8. Aplicación web e infraestructura

La primera versión deberá contar con:

- Interfaz web adaptable a dispositivos móviles y de escritorio.
- Backend con API REST.
- Base de datos relacional.
- Persistencia de la información entre sesiones.
- Autenticación y autorización.
- Gestión de errores.
- Pruebas automatizadas de las operaciones críticas.
- Documentación de la API.
- Configuración reproducible para ejecución local.
- Despliegue funcional accesible para su utilización.

## 4. Funcionalidades excluidas

Las siguientes características no formarán parte del MVP obligatorio.

### 4.1. Personalización — Versión 0.2

- Álbumes y artistas favoritos.
- Listas y rankings personalizados.
- Álbumes pendientes de escuchar.
- Wishlist de CDs y vinilos.
- Estadísticas personales avanzadas.
- Información avanzada de ediciones.
- Fotografías de conciertos.
- Mejoras de búsqueda y filtrado.
- Visualización del diario musical mediante calendario.

### 4.2. Funcionalidades sociales — Versión 0.3

- Perfiles públicos.
- Seguimiento de usuarios.
- Feed cronológico de actividad de usuarios seguidos.
- Integración de actividad social destacada en la página de Inicio.
- Likes y comentarios.
- Publicación de reseñas.
- Descubrimiento de usuarios.
- Moderación de contenido público.

### 4.3. Descubrimiento musical — Versión 0.4

- Recomendaciones musicales.
- Compatibilidad musical entre usuarios.
- Rankings y listas compartidas.
- Descubrimiento de artistas.
- Integraciones musicales adicionales.
- Estadísticas avanzadas.

### 4.4. Plataforma ampliada — Versión 1.0

- Aplicación móvil.
- Notificaciones.
- Integraciones con servicios de reproducción musical.
- Descubrimiento de conciertos.
- Repertorios musicales (*setlists*).
- Resúmenes anuales.
- Mejoras avanzadas de rendimiento y escalabilidad.

Las funcionalidades posteriores a la versión 0.1 podrán revisarse y reorganizarse según las necesidades del proyecto.

## 5. Reglas de negocio principales

La primera versión deberá cumplir las siguientes reglas:

1. Los nombres de usuario y correos electrónicos serán únicos.
2. Las operaciones personales requerirán autenticación.
3. Un usuario únicamente podrá modificar sus propios registros.
4. Las valoraciones admitirán valores desde 0,5 hasta 5 estrellas, en incrementos de 0,5.
5. Las valoraciones serán opcionales. La ausencia de puntuación no se representará mediante un valor de cero.
6. Cada usuario podrá valorar los álbumes independientemente del resto.
7. Un álbum podrá estar asociado a varios artistas.
8. Una publicación podrá disponer de varias ediciones físicas.
9. Una edición podrá formar parte de las colecciones de distintos usuarios.
10. Un usuario podrá poseer varias copias de una misma edición.
11. Añadir un álbum a la colección física no implicará haberlo escuchado.
12. Registrar un concierto no obligará a escribir una reseña ni asignar una puntuación.
13. No se podrán registrar como asistidos conciertos con fecha futura.
14. Eliminar una reseña no eliminará el álbum asociado del catálogo.
15. Los datos musicales compartidos deberán evitar duplicidades innecesarias.
16. Las referencias a entidades externas deberán conservar identificadores estables.
17. Los datos personales serán privados por defecto.
18. Las futuras funciones sociales deberán respetar la configuración de privacidad de los usuarios.

## 6. Criterios de aceptación

El MVP se considerará completado cuando:

- [ ] Un usuario pueda registrarse e iniciar sesión.
- [ ] Las cuentas y los datos personales estén protegidos.
- [ ] Se puedan buscar álbumes y EPs reales.
- [ ] Se pueda consultar una ficha musical.
- [ ] Se puedan registrar escuchas.
- [ ] Se puedan valorar álbumes mediante estrellas.
- [ ] Se puedan crear y modificar reseñas.
- [ ] Se pueda consultar el diario musical.
- [ ] Se puedan registrar conciertos.
- [ ] Se puedan valorar y reseñar conciertos.
- [ ] Se pueda consultar el historial de conciertos.
- [ ] Se puedan registrar CDs y vinilos.
- [ ] Se puedan gestionar varias copias físicas.
- [ ] Se pueda consultar y editar la colección.
- [ ] El perfil muestre los datos de actividad.
- [ ] La información persista entre sesiones.
- [ ] La aplicación funcione en móvil y escritorio.
- [ ] Las operaciones críticas estén probadas.
- [ ] La API esté documentada.
- [ ] La aplicación pueda ejecutarse localmente.
- [ ] Exista un despliegue funcional.
- [ ] El repositorio incluya documentación suficiente para instalar y comprender el sistema.
- [ ] Una sesión válida permita acceder directamente a la zona privada.
- [ ] El usuario autenticado acceda a Inicio como página principal.
- [ ] La navegación principal incluya Inicio, Buscar, Añadir, Actividad y Perfil.
- [ ] El usuario pueda iniciar el registro de escuchas, conciertos y elementos físicos desde Añadir.
- [ ] Se puedan buscar conciertos registrados en la aplicación.
- [ ] Se puedan buscar y consultar ediciones físicas disponibles en Groove.
- [ ] La sección Actividad muestre cronológicamente los registros personales.
- [ ] El Perfil permita acceder al Diario, Conciertos y Colección.

## 7. Límites del desarrollo

El alcance de Groove v0.1 se mantendrá centrado en la experiencia individual del usuario.

Las funcionalidades adicionales identificadas durante el desarrollo se registrarán como posibles ampliaciones y no se incorporarán automáticamente al MVP.

El proyecto seguirá un desarrollo incremental, adaptado a la disponibilidad y compatibilidad con la universidad.

El objetivo será priorizar un producto funcional, estable y mantenible frente a la incorporación de funcionalidades innecesarias.
