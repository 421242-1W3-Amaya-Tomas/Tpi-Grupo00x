# 🐾 Proyecto Veterinaria

Este es un proyecto de software de escritorio (o web, ¡especifícalo aquí!) para la gestión de una clínica veterinaria. El **núcleo principal del proyecto es el sistema de turnos**, diseñado para optimizar la organización y la atención de pacientes.

## 👤 Roles de Usuario

El sistema está diseñado para ser utilizado por múltiples roles dentro de la clínica, cada uno con sus permisos y vistas específicas:

* **Administrador:** Control total del sistema, gestión de usuarios, configuración y acceso a reportes.
* **Veterinario:** Acceso a su agenda de turnos, historial clínico de pacientes y gestión de consultas.
* **Empleado (Recepción):** Creación, modificación y cancelación de turnos, registro de pacientes y clientes.

## 🚀 Puesta en Marcha

Para levantar el proyecto en un entorno de desarrollo local, sigue estos pasos indispensables:

### 1. Backend (API)

El primer paso es levantar el servidor de la API:

1.  Navega al directorio `..\Backend\` del proyecto.
2.  Abre la solución `Veterinaria.sln` (preferiblemente con Visual Studio).
3.  Inicia el proyecto (presionando F5 o el botón de "Iniciar") para que la API esté en ejecución.

### 2. Base de Datos (SQL)

Para que la API funcione, la base de datos debe estar correctamente inicializada.

**Importante:** Los scripts deben ejecutarse en el orden especificado.

1.  Abre tu gestor de base de datos (como SQL Server Management Studio).
2.  Ejecuta el script `1.sql`.
3.  Una vez que `1.sql` haya finalizado exitosamente, ejecuta el script `2.sql`.

¡Una vez completados estos pasos, el sistema debería estar operativo!

## 🛠️ Tecnologías (Ejemplo)

*(Esta sección es opcional, pero recomendada. Puedes completarla)*

* **Backend:** .NET
* **Base de Datos:** SQL Server
* **Frontend:** (Especificar si es WinForms, WPF, Angular, React, etc.)

## 👥 Integrantes del Equipo

* **Pablo Biasco**
* **Nahuel Gatica**
* **Benja Polzoni**
* **Fran Alberioni**
* **Thiago Caseres**
* **Tomas Amaya**
