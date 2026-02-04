# Sistema de Gestión Hospitalaria - Chekinmed (Sep-Dic 2025)

Este proyecto es un sistema de gestión diseñado para optimizar los procesos hospitalarios, incluyendo la automatización mediante agentes inteligentes y el control de inventarios y ventas.

## 🤖 Módulos de Agentes Inteligentes
El sistema integra varios agentes en formato JSON para la gestión de datos:
* **Agente de Búsqueda:** Localización rápida de expedientes y recursos.
* **Agente de Drive:** Gestión y almacenamiento de documentos en la nube.
* **Agente de Mails:** Automatización de notificaciones y comunicaciones.
* **Intérprete:** Procesamiento de datos y lógica del sistema.

## 📊 Estructura de la Base de Datos
El corazón del sistema se basa en un modelo relacional con las siguientes entidades principales:

### 1. Calendario
Permite el seguimiento temporal de todas las citas.
* **Campos:** `Fecha_id` (PK), `Anio`, `Mes`, `Dia`.

### 2. Productos
Catálogo detallado de suministros hospitalarios.
* **Campos:** `Producto_id` (PK), `Nombre`, `Categoria`, `Origen`.

## 🛠️ Tecnologías Utilizadas
* **Git/GitHub:** Control de versiones.
* **N8N:** Configuración de agentes.
* **SQL:** Estructura de datos (Modelado lógico).

## 👥 Equipo de Trabajo
Agradecimientos a los integrantes de este proyecto:
* **David Navarro** - [Rol: Especialista en Bases de Datos y Documentación] 
* **Agustina Mendoza** - [Rol: ej. Desarrollo de Agentes] 
* **Marco Ortega** - [Rol:Especialista Base de Datos y Desarrollo de Agentes]
* **Maximo Unrrein** - [Rol:Diseño UX]
* **Graciela Blanco** - [Rol:Pruebas, Documentacion y Estrátegia de Venta]
