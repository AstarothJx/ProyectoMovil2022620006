# ProyectoMovil2022620006

Repositorio del proyecto final de Programación Móvil:
[AstarothJx/ProyectoMovil2022620006](https://github.com/AstarothJx/ProyectoMovil2022620006/tree/main)

## 📱 Descripción

**Tripmates** es una aplicación Android desarrollada como proyecto escolar, cuyo propósito principal es gestionar viajes y facilitar el control de gastos, itinerarios y listas de empaque. Ofrece sincronización de datos entre dispositivos, permitiendo que varios usuarios colaboren y compartan la información de un mismo viaje en tiempo real.

## 🎯 Objetivo General

Ofrecer una plataforma colaborativa donde los usuarios puedan planificar sus viajes y compartir información de gastos, itinerarios y equipaje de manera eficiente y sincronizada.

## 🛠️ Stack Tecnológico

* **Lenguaje principal:** Kotlin
* **UI:** Jetpack Compose
* **Base de datos local:** SQLite (DBHelper)
* **Backend y sincronización:** Servicios REST en PHP conectados a MySQL
* **Manejo de sesiones y modelos:** Objetos de dominio en Kotlin

## 💻 Requisitos

* Android 14.0 o superior
* Android Studio Ladybug o superior
* JDK 11 o superior

## ⚙️ Configuración e Instalación

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/AstarothJx/ProyectoMovil2022620006.git
   ```
2. Abrir en Android Studio.
3. Actualizar la URL del API en `Constantes.kt`.
4. Sincronizar Gradle.
5. Ejecutar en emulador o dispositivo.

## ✨ Características Principales

* Gestión de usuarios (registro y login).
* Creación, edición y borrado de viajes.
* Registro y seguimiento de gastos.
* Planificación de itinerarios diarios.
* Checklist de empaque interactivo.
* Sincronización en tiempo real.

## 💾 Estructura de Datos

* **Persistencia local:** SQLite (DBHelper.kt).
* **Modelos:** Usuario, Viaje, Gasto, ItemEmpaque, Itinerario, Sesion.
* **CRUD:** Peticiones HTTP a servicios PHP.
* **Formato de datos:** JSON.

## ✅ Validaciones y Tests

* Verificación de CRUD en viajes y gastos.
* Sincronización multiusuario en tiempo real.
* Funcionalidad completa de itinerarios y empaque.
* Ajuste de UI (modo oscuro/claro).

## 📬 Contacto

**Lisset Ameyalli Almaraz Paulín** – [joshuacasram@outlook.com](mailto:joshuacasram@outlook.com)

**Joshua Castro Ramírez** – [joshuacasram@outlook.com](mailto:joshuacasram@outlook.com)

**Fernando Diaz Hidalgo** – [ferdiazhidalgo1105@gmail.com](mailto:ferdiazhidalgo1105@gmail.com)
