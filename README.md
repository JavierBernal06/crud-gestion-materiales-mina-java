# Sistema de Gestión e Inventario de Materiales Mineros (Gestión Mina)

## Creadores / Equipo
* Francisco Javier Bernal Calvo
* Diego Alejandro Torres Salas
* Joaquín Dávila Arenas

## Descripción
Aplicación Java orientada a la administración, trazabilidad y control de inventario de materiales en una operación minera. El sistema implementa las operaciones CRUD (**Create, Read, Update, Delete**) para la gestión de usuarios, materiales e historial de expediciones de insumos, además de permitir la generación de reportes en PDF.

## Archivos Principales del Proyecto
* `src/main`: Código fuente del proyecto en Java con la estructura del modelo, vistas e implementación de la base de datos.
* `BDMinasScript.txt`: Script de creación de la base de datos MySQL (`GestionMina`), tablas, usuario predeterminado y permisos.
* `Reporte_Inventario_*.pdf`: Ejemplo de reporte exportado por el sistema.
* `pom.xml`: Archivo de configuración de Maven con las dependencias del proyecto.
* `instrucciones`: Guía de uso y credenciales del sistema.

## Información del Proyecto, Configuraciones e Instrucciones
* **Lenguaje:** Java (JDK 11 o superior)
* **Gestor de Dependencias:** Apache Maven
* **Base de Datos:** MySQL / MariaDB

---

## 🚀 Guía de Configuración y Ejecución

### 1. Configuración de la Base de Datos
1. Abre tu gestor de MySQL (por ejemplo, MySQL Workbench, phpMyAdmin o consola).
2. Ejecuta el script **`BDMinasScript.txt`** incluido en este repositorio.
3. El script creará automáticamente:
   * La base de datos `GestionMina`.
   * Las tablas `usuarios`, `materiales` y `expediciones`.
   * El usuario de base de datos `usuario_mina@localhost` con la contraseña `password123`.
   * El usuario administrador inicial del sistema:
     * **Usuario:** `admin`
     * **Contraseña:** `admin123`

### 2. Ejecución desde la IDE / Proyecto
1. Abrir o importar el proyecto como proyecto Maven en tu IDE (IntelliJ IDEA, NetBeans o Eclipse).
2. Asegurarse de que el servicio de MySQL esté corriendo en `localhost`.
3. Compilar y ejecutar la clase principal en `src/main/java/...` o generar/ejecutar el archivo `.jar`.
4. Iniciar sesión con las credenciales de administrador (`admin` / `admin123`).

## Imágenes
![Pantalla o reporte del proyecto](Reporte_Inventario_1764747345260.pdf)
