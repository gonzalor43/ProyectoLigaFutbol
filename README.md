# Sistema de Gestión para Liga de Fútbol

Este proyecto tiene como objetivo desarrollar un sistema integral para gestionar jugadores, clubes, estadísticas, y encuentros de un campeonato de fútbol. Proporciona herramientas para registrar, organizar y analizar información clave relacionada con los torneos, además de funcionalidades avanzadas como la confección de fixtures y control de transferencias.

---

## **Características Principales**
### **Descripción General**
El sistema permitirá:
- **Gestión de jugadores, clubes y estadios:** Registro y control seguro de datos personales y estadísticos.
- **Control de torneos:** Creación de fixtures, asignación de partidos, y actualización de tablas de posiciones.
- **Seguimiento de transferencias:** Confirmación o rechazo de solicitudes entre clubes.
- **Estadísticas de encuentros:** Registro de incidencias y hechos relevantes en cada partido.
- **Gestión de usuarios:** Control de permisos por tipo de usuario, auditoría de modificaciones y creación de nuevos usuarios.

---

## **Estructura del Proyecto**
### **1. Módulo de Jugadores**
- Gestión completa de jugadores registrados (registro, modificación, baja).
- Generación de reportes sobre jugadores.

### **2. Módulo de Equipos**
- Registro de equipos afiliados a la asociación de fútbol.
- Gestión de la eliminación de clubes en caso de desvinculación.
- Reportes detallados sobre los clubes.

### **3. Módulo de Estadios**
- Registro, modificación y baja de estadios afiliados a la asociación.
- Generación de reportes sobre estadios.

### **4. Módulo de Técnicos**
- Gestión de técnicos registrados (registro, modificación, baja).

### **5. Módulo de Transferencias**
- Confirmación o rechazo de solicitudes de transferencias por parte de clubes.
- Solicitud de registro de jugadores entre clubes.
- Reportes sobre transferencias.

### **6. Módulo de Campeonatos**
- Registro de nuevos torneos y confección de fixtures.
- Asignación de partidos y fechas para encuentros.
- Generación y actualización de la tabla de posiciones.
- Registro de alineaciones (titulares y suplentes) para cada partido.
- Registro de campeones y vicecampeones.

### **7. Módulo de Árbitros**
- Registro de estadísticas e incidencias de los partidos por parte de los árbitros.

### **8. Módulo de Usuarios**
- Creación y eliminación de usuarios (administradores, árbitros, etc.).
- Control de acceso mediante permisos por tipo de usuario.

---

## **Requerimientos No Funcionales**
### **1. Seguridad**
- Control de permisos basado en roles:
  - **Árbitros**
  - **Operarios**
  - **Equipos**
  - **Administradores**
- Garantiza limitaciones de acceso para cada tipo de usuario.

### **2. Auditoría**
- Registro de modificaciones y eliminaciones para asegurar la trazabilidad.
- Recuperación de información en caso de errores.

---

## **Tecnologías Utilizadas**
- **Frontend:** HTML5 y CSS3 para la estructura y diseño.
- **Backend:** Framework moderno para la gestión de datos.
- **Base de Datos:** Diseño relacional para almacenar información de manera segura y eficiente.

---

## **Funcionalidades Clave**
- **Gestión integral:** Control total sobre datos de jugadores, clubes y torneos.
- **Reportes detallados:** Estadísticas claras para análisis.
- **Seguridad avanzada:** Sistema de permisos por rol y auditoría completa.
- **Flexibilidad:** Creación de torneos y calendarización de partidos adaptada a necesidades específicas.

---

## **Tecnologías Utilizadas**
- **Backend:**
  - Python
  - Django 
- **Frontend:**
  - HTML5
  - CSS3
  - Bootstrap 
  - JavaScript 

---

## Instrucciones para descomprimir
1. Descarga el archivo comprimido `proyectoLiga.zip` del repositorio.
2. Usa cualquier herramienta para descomprimir, como:
   - En Windows: Haz clic derecho > "Extraer aquí".
   - En Linux/MacOS: Usa el siguiente comando en la terminal:
     ```bash
     unzip proyectoLiga.zip
     ```
