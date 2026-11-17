# Bocetos de interfaz — Groove

## 1. Objetivo

Este documento recoge las decisiones iniciales de diseño de las pantallas de Groove.

Los bocetos se han elaborado para estudiar la distribución de contenidos, los componentes principales y la adaptación de la interfaz a dispositivos móviles y de escritorio.

Constituyen la base para desarrollar posteriormente los prototipos en Figma.

Los bocetos son representaciones de baja fidelidad (*wireframes*). No definen todavía la identidad visual definitiva de Groove.

La estructura funcional se encuentra documentada en [Navegación](navegacion.md).

El estado de cada pantalla se encuentra en [Inventario de pantallas](inventario-pantallas.md).

## 2. Archivos de referencia

Los bocetos se han elaborado en draw.io. El archivo editable original se conserva localmente y no forma parte del repositorio.

Las exportaciones disponibles en GitHub son:

- `bocetos/movil.png`: lámina general de las pantallas móviles.
- `bocetos/escritorio.png`: lámina general de las pantallas de escritorio.

### Bocetos móviles

![Bocetos móviles de Groove](bocetos/movil.png)

### Bocetos de escritorio

![Bocetos de escritorio de Groove](bocetos/escritorio.png)

## 3. Principios generales del diseño

### 3.1. Enfoque

El diseño seguirá un enfoque centrado inicialmente en dispositivos móviles, adaptándose posteriormente a escritorio.

Se priorizarán:

- Navegación sencilla.
- Accesos rápidos a las funciones principales.
- Presentación visual del contenido musical.
- Coherencia entre pantallas.
- Componentes reutilizables.
- Separación de información personal y actividad social.

### 3.2. Estilo de los bocetos

Los diseños actuales utilizan:

- Blanco, negro y grises.
- Iconos sencillos.
- Bordes redondeados.
- Tarjetas rectangulares.
- Cuadrículas de portadas.
- Tipografía provisional.
- Elementos visuales de sustitución.

Los colores, fuentes, imágenes y dimensiones definitivas se concretarán durante las siguientes fases de diseño.

### 3.3. Adaptación a dispositivos

**Móvil**

- Cabecera superior.
- Barra inferior de navegación en la zona privada.
- Contenido organizado verticalmente.
- Cuadrículas y carruseles adaptados al ancho.
- Paneles inferiores para acciones rápidas.

**Escritorio**

- Menú lateral en la zona privada.
- Mayor aprovechamiento del espacio horizontal.
- Distribuciones en columnas.
- Cuadrículas de mayor capacidad.
- Diálogos centrados para acciones rápidas.

---

## 4. Zona pública

### 4.1. P-01 — Bienvenida

La pantalla presenta Groove mediante:

- Cabecera con logotipo.
- Imagen de fondo provisional.
- Lema «Tu música, tu historia».
- Descripción de la aplicación.
- Tres bloques funcionales: Diario musical, Conciertos y Colección física.
- Botones Crear cuenta e Iniciar sesión.

En móvil se utiliza una distribución vertical.

En escritorio se utiliza una composición de dos zonas, con el contenido principal y el espacio destinado a la imagen.

### 4.2. P-02 — Registro

Mantiene la identidad visual de Bienvenida.

Incluye:

- Nombre de usuario.
- Correo electrónico.
- Contraseña.
- Confirmación de contraseña.
- Acción Crear cuenta.
- Acceso a Inicio de sesión.

En escritorio los campos se distribuyen en dos columnas.

### 4.3. P-03 — Inicio de sesión

Incluye:

- Nombre de usuario o correo electrónico.
- Contraseña.
- Acción Iniciar sesión.
- Acceso a Registro.
- Acceso a recuperación de contraseña.

Mantiene la estructura visual de Registro.

---

## 5. Navegación privada

### 5.1. Estructura móvil

Las pantallas principales comparten:

- Cabecera con marca Groove.
- Zona central de contenido.
- Barra inferior con Inicio, Buscar, Añadir, Actividad y Perfil.

La opción activa se diferencia mediante un fondo destacado.

### 5.2. Estructura de escritorio

Las pantallas principales comparten:

- Menú lateral izquierdo.
- Logotipo y nombre Groove.
- Cinco opciones de navegación.
- Zona principal de contenido.

La opción activa queda identificada visualmente.

El menú lateral se mantiene consistente entre las pantallas.

---

## 6. P-04 — Inicio

### Móvil

Incluye:

- Saludo personalizado.
- Texto introductorio.
- Carrusel de Escuchas recientes.
- Tarjetas de Conciertos destacados.
- Carrusel Tu colección.
- Accesos para consultar cada sección completa.

### Escritorio

Mantiene los mismos contenidos, adaptándolos al mayor espacio horizontal.

Los carruseles permiten mostrar más elementos simultáneamente.

Los conciertos se organizan en tarjetas horizontales.

No se añaden secciones funcionales diferentes a las de móvil.

---

## 7. P-05 — Buscar

### Móvil

Incluye:

- Título Buscar.
- Campo de búsqueda.
- Selector de categorías.
- Listado de resultados.

Los resultados incluyen imagen o portada e información básica.

### Escritorio

Mantiene el buscador y las categorías.

Los resultados musicales se representan principalmente mediante una cuadrícula de portadas o tarjetas.

El contenido podrá adaptarse según el tipo de resultado.

---

## 8. M-01 — Añadir

Añadir se representa como una acción global.

### Móvil

Se utiliza un panel inferior superpuesto sobre la pantalla actual.

Contiene:

- Título «¿Qué quieres añadir?».
- Registrar escucha.
- Registrar concierto.
- Añadir a colección.

### Escritorio

Se utiliza un diálogo centrado sobre la pantalla de origen, con las mismas tres operaciones.

El contenido de fondo queda visualmente atenuado.

El menú podrá cerrarse sin cambiar la pantalla anterior.

---

## 9. P-15 — Actividad

### Móvil

Incluye:

- Título Actividad.
- Selector Mi actividad / Siguiendo.
- Entradas cronológicas agrupadas por periodos.
- Tarjetas de escuchas, conciertos y elementos físicos.

Las tarjetas muestran información apropiada para cada tipo de registro.

### Escritorio

Mantiene la misma estructura.

Las tarjetas aprovechan el espacio horizontal disponible.

Se contempla un control de filtrado por tipo de actividad.

La vista Siguiendo se reserva para la v0.3.

---

## 10. P-13 — Perfil

La sección Perfil incorpora una navegación secundaria mediante cuatro pestañas:

- Perfil.
- Diario.
- Colección.
- ListenList.

### 10.1. Perfil principal

El boceto incluye:

- Nombre de usuario.
- Acceso a la identidad personal.
- Contadores de álbumes, conciertos y colección.
- Álbumes favoritos.
- Actividad reciente.
- Resumen de los últimos registros.

El bloque Resumen muestra:

- Última escucha.
- Último concierto.
- Último elemento añadido a la colección.

En escritorio los contadores se distribuyen horizontalmente y las tarjetas del resumen se presentan en una misma fila.

Los álbumes favoritos están previstos para la v0.2.

### 10.2. Diario

Se utiliza una estructura cronológica agrupada por meses.

Cada entrada incluye:

- Fecha.
- Imagen o icono del contenido.
- Título o artista.
- Valoración cuando exista.

El Diario deberá incorporar filtros Todos, Álbumes / EPs y Conciertos.

Estos filtros están definidos funcionalmente, aunque su presentación visual todavía debe completarse en los bocetos.

En escritorio se aprovecha el espacio disponible para distribuir las entradas en varias columnas.

### 10.3. Colección

Se utiliza una biblioteca visual de copias físicas.

Incluye:

- Buscador interno.
- Filtros Todos, Vinilos y CDs.
- Botón Añadir.
- Cuadrícula de elementos.

En móvil se utiliza una cuadrícula de cuatro columnas.

En escritorio se amplía el número de columnas manteniendo el mismo contenido.

### 10.4. ListenList

Se utiliza una biblioteca visual de álbumes y EPs pendientes.

Incluye:

- Buscador interno.
- Filtros Todos, Álbumes y EPs.
- Botón Añadir.
- Cuadrícula de publicaciones.

Su estructura mantiene coherencia con Colección, aunque representa un tipo de información diferente.

ListenList estará disponible desde la v0.2.

---

## 11. Componentes reutilizables identificados

Los bocetos permiten identificar los siguientes componentes:

- Logotipo y marca Groove.
- Cabecera pública.
- Cabecera móvil privada.
- Barra inferior de navegación.
- Menú lateral de escritorio.
- Selector de pestañas.
- Campos de búsqueda.
- Campos de formulario.
- Botones principales y secundarios.
- Tarjetas de álbum.
- Tarjetas de concierto.
- Tarjetas de actividad.
- Elementos de cuadrícula.
- Indicadores de valoración.
- Contadores.
- Menú Añadir.
- Filtros de categorías.

Estos componentes servirán de referencia durante la creación de componentes editables en Figma.

---

## 12. Pantallas pendientes de bocetado

Todavía deben diseñarse:

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

También deberán concretarse los estados vacíos y los mensajes de error de las pantallas principales.

Los formularios podrán combinarse visualmente cuando compartan un mismo recorrido.

---

## 13. Evolución hacia Figma

Los bocetos serán utilizados como referencia para crear diseños editables en Figma.

La siguiente fase deberá:

1. Aplicar la identidad visual definitiva.
2. Establecer tipografías y colores.
3. Definir componentes reutilizables.
4. Construir las pantallas principales.
5. Diseñar las fichas y formularios pendientes.
6. Incorporar navegación interactiva.
7. Comprobar la adaptación responsive.
8. Diferenciar las funcionalidades del MVP de las futuras.

La documentación se actualizará cuando se aprueben nuevos diseños o se introduzcan cambios relevantes.
