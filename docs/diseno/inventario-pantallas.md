# Inventario de pantallas — Groove

## 1. Objetivo

Este documento identifica todas las pantallas, vistas internas, modales y formularios previstos para Groove.

Su finalidad es mantener un registro claro de los elementos de la interfaz, su alcance funcional, la versión en la que estarán disponibles y el estado de su diseño.

Se utilizará como referencia durante:

- Elaboración de bocetos.
- Diseño de prototipos en Figma.
- Implementación del frontend.
- Pruebas de navegación.
- Evolución de las diferentes versiones.

El inventario se mantendrá actualizado cuando se incorporen, modifiquen o retiren elementos de la interfaz.

## 2. Convenciones

### 2.1. Identificadores

| Prefijo | Tipo | Descripción |
|---|---|---|
| P | Pantalla | Página o ruta navegable |
| V | Vista | Pestaña, filtro o variante interna |
| M | Modal | Interfaz superpuesta |
| F | Formulario | Registro o edición de información |

Los identificadores serán estables y no deberán reutilizarse para funcionalidades diferentes.

### 2.2. Estado de diseño

- **Diseñado:** existe un boceto aproximado en móvil y escritorio.
- **Pendiente:** todavía no se ha elaborado el boceto.
- **Por definir:** el alcance o la presentación necesitan concretarse.

El estado Diseñado no implica que exista un prototipo definitivo ni una implementación funcional.

### 2.3. Versiones

- **v0.1:** MVP.
- **v0.2:** personalización.
- **v0.3:** red social.
- **v0.4:** descubrimiento.
- **v1.0:** plataforma ampliada.

Los bocetos pueden representar funcionalidades posteriores al MVP.

## 3. Zona pública

| ID | Pantalla | Versión | Boceto |
|---|---|---|---|
| P-01 | Bienvenida | v0.1 | Diseñado |
| P-02 | Registro | v0.1 | Diseñado |
| P-03 | Inicio de sesión | v0.1 | Diseñado |
| P-16 | Recuperación de contraseña | Por concretar | Pendiente |

### P-01 — Bienvenida

Presentación de Groove y de sus principales funcionalidades.

Accesos:

- Registro.
- Inicio de sesión.

### P-02 — Registro

Creación de cuentas de usuario.

Campos principales:

- Nombre de usuario.
- Correo electrónico.
- Contraseña.
- Confirmación de contraseña.

### P-03 — Inicio de sesión

Autenticación mediante credenciales.

Incluye:

- Nombre de usuario o correo electrónico.
- Contraseña.
- Acceso a Registro.
- Acceso a Recuperación de contraseña.

### P-16 — Recuperación de contraseña

Flujo para recuperar el acceso a una cuenta.

Pendiente de definir su alcance y sus pantallas o estados internos.

## 4. Zona privada — Navegación principal

| ID | Pantalla | Versión | Boceto |
|---|---|---|---|
| P-04 | Inicio | v0.1 | Diseñado |
| P-05 | Buscar | v0.1 | Diseñado |
| P-15 | Actividad | v0.1 | Diseñado |
| P-13 | Perfil | v0.1 | Diseñado |

La acción Añadir se identifica como M-01 porque no constituye una pantalla independiente.

### P-04 — Inicio

Pantalla principal de Groove.

Bloques:

- Escuchas recientes.
- Conciertos destacados.
- Tu colección.

### P-05 — Buscar

Consulta de contenido musical.

Categorías:

- Álbumes / EPs.
- Conciertos.
- Ediciones.

### P-15 — Actividad

Historial cronológico de acciones musicales.

Vistas:

- Mi actividad.
- Siguiendo (v0.3).

### P-13 — Perfil

Presentación de la identidad musical del usuario.

Incluye:

- Información personal.
- Contadores.
- Álbumes favoritos (v0.2).
- Actividad reciente.
- Resumen de últimos registros.

Permite acceder a Diario, Colección, futura ListenList y Ajustes.

## 5. Zona privada — Diario y bibliotecas

| ID | Pantalla | Versión | Boceto |
|---|---|---|---|
| P-08 | Diario musical | v0.1 | Diseñado |
| P-11 | Colección física | v0.1 | Diseñado |
| P-17 | ListenList | v0.2 | Diseñado |
| P-14 | Ajustes | v0.1 | Pendiente |

### P-08 — Diario musical

Historial unificado de escuchas y asistencias a conciertos.

Vistas:

- Todos.
- Álbumes / EPs.
- Conciertos.

Los registros se organizarán cronológicamente.

### P-11 — Colección física

Biblioteca de copias físicas del usuario.

Incluye:

- Buscador interno.
- Filtros por formato.
- Cuadrícula de elementos.
- Acción Añadir.

### P-17 — ListenList

Publicaciones pendientes de escuchar.

Incluye:

- Buscador interno.
- Filtros por tipo de publicación.
- Cuadrícula de álbumes y EPs.
- Acción Añadir.

Su diseño está preparado, pero no forma parte del MVP.

### P-14 — Ajustes

Configuración de la cuenta.

Deberá contemplar:

- Datos personales.
- Seguridad de cuenta.
- Cierre de sesión.

Su distribución visual está pendiente de definir.

## 6. Zona privada — Fichas de detalle

| ID | Pantalla | Versión | Boceto |
|---|---|---|---|
| P-06 | Ficha de álbum / EP | v0.1 | Pendiente |
| P-10 | Ficha de concierto | v0.1 | Pendiente |
| P-12 | Detalle de elemento físico | v0.1 | Pendiente |

### P-06 — Ficha de álbum / EP

Contenido:

- Portada.
- Título.
- Artista o artistas.
- Fecha de publicación.
- Tipo de publicación.
- Lista de canciones.
- Valoración personal.
- Acciones de registro y reseña.

### P-10 — Ficha de concierto

Contenido:

- Artista o artistas.
- Fecha.
- Ciudad.
- Recinto.
- Información del concierto.
- Registro personal de asistencia.
- Valoración y reseña.

### P-12 — Elemento físico

Contenido:

- Publicación musical.
- Formato.
- Edición.
- Información de la copia.
- Acciones de edición y eliminación.

## 7. Modales y paneles

| ID | Elemento | Versión | Boceto |
|---|---|---|---|
| M-01 | Menú Añadir | v0.1 | Diseñado |
| M-02 | Confirmación de eliminación | v0.1 | Pendiente |

### M-01 — Menú Añadir

Acción global de la navegación privada.

Opciones:

- Registrar escucha.
- Registrar concierto.
- Añadir a colección.

Presentación:

- Móvil: panel inferior.
- Escritorio: diálogo centrado.

### M-02 — Confirmación de eliminación

Componente reutilizable para confirmar la eliminación de registros personales.

## 8. Formularios

| ID | Formulario | Versión | Boceto |
|---|---|---|---|
| F-01 | Registrar / editar escucha | v0.1 | Pendiente |
| F-02 | Valorar / reseñar álbum o EP | v0.1 | Pendiente |
| F-03 | Registrar / editar concierto | v0.1 | Pendiente |
| F-04 | Valorar / reseñar concierto | v0.1 | Pendiente |
| F-05 | Añadir / editar copia física | v0.1 | Pendiente |

Los formularios podrán compartir componentes e integrarse en recorridos comunes.

### F-01 — Escucha

Información principal:

- Álbum o EP.
- Fecha de escucha.
- Datos adicionales permitidos.

### F-02 — Valoración y reseña musical

Información principal:

- Publicación asociada.
- Valoración opcional.
- Reseña opcional.

### F-03 — Concierto

Información principal:

- Artista.
- Fecha.
- Recinto.
- Ciudad.
- Asistencia registrada.

### F-04 — Valoración y reseña de concierto

Información principal:

- Concierto asociado.
- Valoración opcional.
- Reseña opcional.

### F-05 — Copia física

Información principal:

- Publicación musical.
- Formato.
- Edición, cuando se conozca.
- Información de la copia.

## 9. Vistas y filtros

| ID | Pantalla | Vista | Versión |
|---|---|---|---|
| V-01 | P-05 Buscar | Álbumes / EPs | v0.1 |
| V-02 | P-05 Buscar | Conciertos | v0.1 |
| V-03 | P-05 Buscar | Ediciones | v0.1 |
| V-04 | P-15 Actividad | Mi actividad | v0.1 |
| V-05 | P-15 Actividad | Siguiendo | v0.3 |
| V-06 | P-08 Diario | Todos | v0.1 |
| V-07 | P-08 Diario | Álbumes / EPs | v0.1 |
| V-08 | P-08 Diario | Conciertos | v0.1 |
| V-09 | P-11 Colección | Todos | v0.1 |
| V-10 | P-11 Colección | Vinilos | v0.1 |
| V-11 | P-11 Colección | CDs | v0.1 |
| V-12 | P-17 ListenList | Todos | v0.2 |
| V-13 | P-17 ListenList | Álbumes | v0.2 |
| V-14 | P-17 ListenList | EPs | v0.2 |

Los filtros no requerirán pantallas independientes.

## 10. Estados transversales

Las pantallas deberán contemplar los siguientes estados cuando correspondan:

- **Inicial:** antes de introducir datos o seleccionar una opción.
- **Cargando:** mientras se obtiene información.
- **Con contenido:** cuando existen datos disponibles.
- **Vacío:** cuando el usuario todavía no ha registrado información.
- **Sin resultados:** cuando una búsqueda o filtro no devuelve coincidencias.
- **Error:** cuando una operación no puede completarse.
- **Confirmación:** después de completar una operación, cuando resulte necesario.

Estos estados no tendrán identificadores de pantalla independientes.

Su representación podrá resolverse mediante variantes de componentes durante el prototipado.

## 11. Trazabilidad con la especificación original

Se conservarán las siguientes referencias históricas:

| Identificador original | Equivalencia actual | Motivo |
|---|---|---|
| P-07 — Valoración de álbum | F-02 | Funcionalidad integrada en formulario |
| P-09 — Conciertos | V-08 | Vista filtrada dentro del Diario |

P-07 y P-09 no se reutilizarán para pantallas nuevas.

Los nuevos identificadores son:

- P-16 — Recuperación de contraseña.
- P-17 — ListenList.

## 12. Resumen del estado de diseño

### Diseñado

**Zona pública**

- P-01 — Bienvenida.
- P-02 — Registro.
- P-03 — Inicio de sesión.

**Zona privada**

- P-04 — Inicio.
- P-05 — Buscar.
- P-15 — Actividad.
- P-13 — Perfil.
- P-08 — Diario.
- P-11 — Colección.
- P-17 — ListenList.

**Elementos auxiliares**

- M-01 — Menú Añadir.

Todos estos elementos cuentan con bocetos aproximados de móvil y escritorio.

### Pendiente de diseñar

- P-06 — Ficha de álbum / EP.
- P-10 — Ficha de concierto.
- P-12 — Detalle de elemento físico.
- P-14 — Ajustes.
- P-16 — Recuperación de contraseña.
- M-02 — Confirmación de eliminación.
- F-01 — Registrar / editar escucha.
- F-02 — Valorar / reseñar álbum o EP.
- F-03 — Registrar / editar concierto.
- F-04 — Valorar / reseñar concierto.
- F-05 — Añadir / editar copia física.

Los elementos pendientes se abordarán progresivamente, priorizando las funcionalidades necesarias para el MVP.

## 13. Mantenimiento del inventario

Cada vez que se incorpore una nueva pantalla o funcionalidad se deberá:

1. Comprobar si ya existe un elemento que pueda reutilizarse.
2. Asignar un identificador estable cuando corresponda.
3. Definir su responsabilidad.
4. Establecer la versión prevista.
5. Registrar sus accesos principales.
6. Actualizar el estado del boceto.
7. Incorporar los cambios a la documentación de navegación.

El inventario será la referencia principal para controlar el diseño y la implementación de la interfaz.
