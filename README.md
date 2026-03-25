# 🎓 Math Games: Gamification & Educational Management System

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)

Este proyecto es mi **Tesis de Grado** para la **Licenciatura en Análisis de Sistemas**. Es una solución integral que utiliza la gamificación para potenciar el aprendizaje de las matemáticas, permitiendo un seguimiento pedagógico detallado a través del análisis de datos.

---

## 💡 El Problema y la Solución

La falta de herramientas que motiven al alumno y brinden datos precisos al docente es un reto actual. Esta plataforma resuelve esto mediante:

* **Gamificación Activa:** Aprendizaje basado en juegos con registros en tiempo real.
* **Gestión Basada en Datos:** Transformación de métricas en reportes analíticos.
* **Automatización Administrativa:** Generación de documentos PDF y control de roles.

---

## ✨ Características Principales

### 👨‍🏫 Módulo Docente (Analytics)
* **Seguimiento de Rendimiento:** Dashboards con puntajes, niveles y tiempos.
* **Reportes PDF:** Generación automatizada de informes de progreso.

### 🎮 Módulo Alumno (Gamificación)
* **Desafíos Progresivos:** Juegos con dificultad dinámica.
* **Historial Personal:** Evolución y mejores marcas del estudiante.

### ⚙️ Módulo Administrador
* **Control de Acceso (RBAC):** Gestión centralizada de usuarios y permisos.
* **Mantenimiento:** Supervisión de la integridad de la base de datos.

---

## 🛠️ Stack Tecnológico

| Capa | Tecnologías |
| :--- | :--- |
| **Backend** | Node.js, Express.js |
| **Base de Datos** | PostgreSQL, Sequelize ORM |
| **Seguridad** | JWT, Bcryptjs |
| **Reportes** | PDFKit (Documentos dinámicos) |

---

## 📊 Arquitectura de Datos

Como **Licenciado en Sistemas**, diseñé un esquema relacional normalizado para garantizar escalabilidad y consistencia:
* **UUIDs:** Identificadores únicos y seguros para cada registro.
* **Relaciones:** Estructura vinculada entre Usuarios, Sesiones de Juego (Scores) y Dificultad.

