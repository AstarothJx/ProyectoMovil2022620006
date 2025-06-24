## ProyectoMovil2022620006
# Tripmates
Repositorio del proyecto final de Programación Móvil

## 📱 Descripción

**Tripmates** es una aplicación Android desarrollada como proyecto escolar, cuyo propósito principal es gestionar viajes y facilitar el control de gastos, itinerarios y listas de empaque. Ofrece sincronización de datos entre dispositivos, permitiendo que varios usuarios colaboren y compartan la información de un mismo viaje en tiempo real.

## 🧠 Propósito del Proyecto

Brindar una herramienta integral para planificar y administrar viajes de forma colaborativa, donde los usuarios puedan llevar control de gastos, crear itinerarios diarios y gestionar dinámicamente su lista de empaque.

## ⚙️ Tecnologías Utilizadas

* **Lenguaje principal:** Kotlin
* **UI:** Jetpack Compose
* **Base de datos local:** SQLite (DBHelper)
* **Backend y sincronización:** Servicios REST en PHP conectados a MySQL
* **Manejo de sesiones y modelos:** Objetos de dominio en Kotlin

## 📲 Requisitos del Sistema

* Android 8.0 (Oreo) o superior
* Android Studio Arctic Fox o superior
* JDK 11 o superior
* Conexión a Internet para sincronización en tiempo real

## 🔧 Instalación y Configuración

*En desarrollo.* Se planea documentar próximamente los pasos estándar:

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/tu-usuario/tripmates.git
   ```
2. Abrir el proyecto en Android Studio.
3. Configurar la URL del servicio PHP en `Constantes.kt`.
4. Sincronizar dependencias Gradle.
5. Ejecutar la app en emulador o dispositivo real.

## 🧩 Funcionalidades Principales

* Registro y autenticación de usuarios.
* Creación, edición y eliminación de viajes.
* Registro de gastos asociados a cada viaje.
* Planificación de itinerarios por día.
* Lista de empaque interactiva con marcado de elementos.
* Sincronización de datos entre dispositivos en tiempo real.

## 🗄️ Gestión de Datos

* **Persistencia local:** SQLite (`DBHelper.kt`).
* **Modelos:** `Usuario`, `Viaje`, `Gasto`, `ItemEmpaque`, `Itinerario`, `Sesion`.
* **CRUD:** Peticiones HTTP a servicios PHP.
* **Formato de datos:** JSON.

## 🔐 Seguridad

*En proceso de implementación.*
Se planea añadir autenticación por token y validaciones adicionales en el backend.

## 🧪 Pruebas Realizadas

* Creación y sincronización de viajes.
* Registro de gastos desde distintos dispositivos.
* Edición y eliminación de ítems de empaque.
* Planificación de itinerarios y actualización en tiempo real.
* Cambios de preferencias visuales (modo oscuro/claro).

## 🛠️ Mantenimiento y Actualizaciones

Este proyecto se desarrolló con fines educativos y no contempla mantenimiento continuo. El código queda disponible como referencia para estudiantes y desarrolladores.

## 📬 Contacto

**Joshua Castro Ramírez** – [joshuacasram@outlook.com](mailto:joshuacasram@outlook.com)
