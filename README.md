BASES DE DATOS.
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=336791&height=200&section=header&text=Proyecto%20de%20Bases%20de%20Datos&fontSize=50&animation=fadeIn&fontColor=ffffff" />
</div>

# 🗄️ Gestión y Administración de Bases de Datos

👤 **Desarrollador:** Juan Francisco Hernández <br>
🏫 **Institución:** Instituto Nacional de Osicala (INO)  <br>
👨‍🏫 **Módulo / Docente:** Desarrollo de Software - Prof. [Juan Francisco Hernández]

---

## 🏫 Sobre el Instituto Nacional de Osicala

Este proyecto fue desarrollado como parte integral de mi formación en el **Instituto Nacional de Osicala**, orgullosamente ubicado en el departamento de Morazán, El Salvador. El INO se destaca por su compromiso con la educación técnica, preparando a los jóvenes con habilidades tecnológicas actualizadas y preparándonos para los retos del mundo laboral en el área de Tecnologías de la Información.

Quiero extender un agradecimiento especial a mi maestro de Desarrollo de Software, **[Nombre de tu Maestro]**, por su excelente guía, paciencia y por brindarnos las bases sólidas en lógica de programación y estructuración de datos que hicieron posible este proyecto.

---

## 📖 Sobre este Repositorio

Este repositorio contiene los scripts, modelos estructurados y respaldos (backups) de bases de datos desarrollados durante mis clases. 

El objetivo principal de este proyecto es demostrar la capacidad para diseñar, crear y administrar bases de datos relacionales, utilizando buenas prácticas empresariales como:
- Implementación de tipos de datos personalizados (`ENUM`).
- Estructuras no relacionales dentro de SQL usando `JSONB`.
- Mantenimiento estricto de la integridad referencial (Primary Keys y Foreign Keys).

---

## 🛠️ Tecnologías y Herramientas Utilizadas

<div align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/pgAdmin_4-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="pgAdmin4" />
  <img src="https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQL Server" />
  <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</div>

---

## 📂 Estructura del Proyecto

* 📁 **`scripts/`**: Contiene los archivos `.sql` con las sentencias DDL (Data Definition Language) para la creación de tablas y tipos, y DML (Data Manipulation Language) para la inserción de registros de prueba.
* 📁 **`backups/`**: Archivos de respaldo (ej. `accommodation_database_backup`) listos para ser montados y restaurados en cualquier servidor local.
* 📁 **`diagramas/`**: Modelos Entidad-Relación (ERD) que explican de manera visual la arquitectura de las tablas y sus relaciones.

---

## 🚀 Cómo desplegar este proyecto localmente

Si deseas restaurar y probar esta base de datos en tu propia máquina, sigue estos pasos utilizando **pgAdmin 4**:

1. Abre pgAdmin 4 y conéctate a tu servidor PostgreSQL local.
2. Crea una base de datos vacía (ej. `biblioteca_db` o `accommodation_db`).
3. Haz clic derecho sobre la base de datos recién creada y selecciona **Restore...**
4. En la ventana emergente, cambia el filtro de formato a **All Files (*.*)** y selecciona el archivo de backup provisto en la carpeta `/backups` de este repositorio.
5. Haz clic en **Restore**. ¡Listo! Las tablas y datos se cargarán automáticamente.

---

<div align="center">
  <i>Desarrollado con lógica, estructura y pasión por los datos en el corazón de Morazán. 🇸🇻</i>
</div>
