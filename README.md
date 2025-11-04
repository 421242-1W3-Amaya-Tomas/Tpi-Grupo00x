# 🐾 Proyecto Veterinaria 🙉🙈

Este es un proyecto de software de webAPI para la gestión de una clínica veterinaria **(DOGTOR)**. El **núcleo principal del proyecto es el sistema de turnos**, diseñado para optimizar la organización y la atención de pacientes.

## 👤 Roles de Usuario

El sistema está diseñado para ser utilizado por múltiples roles dentro de la clínica, cada uno con sus permisos y vistas específicas:

* **Administrador:** Acceso a su agenda de turnos, administracion de turnos y acceso a reportes.
* **Veterinario:** Acceso a su agenda de turnos y administrar turnos

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
2.  Ejecuta el script `dogtorDB.sql`.
3.  Una vez que `dogtorDB.sql` haya finalizado exitosamente, ejecuta el script `QueryAddTurnosDisponibleLogico.sql`.

¡Una vez completados estos pasos, el sistema debería estar operativo!

## 🛠️ Tecnologías 

* **Backend:** .NET, JWT, Bvcrypt
* **Base de Datos:** SQL Server, Alojada en una sola PC y llamada con una VPN (VPNTailScale)
* **Frontend:** HTML, CSS, JS, Chart.js, SweetAlert, Bootstrap

## 👥 Integrantes del Equipo
* **Pablo Biasco- 411953**
* **Nahuel Gatica- 421310**
* **Benjamin Polzoni- 412056**
* **Franco Alberione- 421432**
* **Tomas Amaya- 421242**
* **Thiago Caseres- 412159**
* **Thiago Caseres**
* **Tomas Amaya**
