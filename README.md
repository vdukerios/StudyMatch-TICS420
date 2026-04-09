# StudyMatch: Descubrimiento de Pares Académicos

## Información Institucional
* **Universidad:** Universidad Adolfo Ibáñez.
* **Facultad:** Facultad de Ingeniería y Ciencias.
* **Curso:** Programación Profesional (TICS420-1-2026).
* **Docentes:** Nicolás Cenzano, Nicolás Escobar, Cristóbal Quijanes.

## Integrantes
* **Integrante 1:** Valentín Duke (Lógica de Negocios, Backend y Arquitectura).
* **Integrante 2:** Fernanda Quiros (Frontend y UI/UX Design).

---

## Propuesta de Valor (The Pitch)
El modelo educativo actual exige una alta carga de trabajo autónomo, estimada en al menos 3 horas de estudio fuera de clases por cada hora cronológica en el aula. Sin embargo, la mayoría de los estudiantes enfrentan este desafío de manera aislada debido a la "Inercia Social" y la falta de afinidad con sus pares académicos.

**StudyMatch** es una plataforma de descubrimiento de pares diseñada para conectar a estudiantes de la UAI que cursan los mismos ramos y buscan compañeros con quienes no solo estudiar, sino también generar afinidad personal. Al integrar habilidades técnicas con intereses personales como hobbies o proyectos, eliminamos la fricción de "acercarse a un extraño" y transformamos el estudio en una instancia de colaboración social segura y validada por el correo institucional.

---

## Lógica del Negocio
La plataforma gestiona el ciclo de vida del estudio colaborativo mediante las siguientes funcionalidades clave:

1.  **Perfil de Afinidad Académica:** Registro de ramos vigentes, carrera y un desglose de fortalezas académicas (ej: "Finanzas" o "React").
2.  **Discovery Basado en Intereses:** Interfaz para explorar perfiles de otros alumnos filtrando por necesidad académica y compatibilidad de estilos o hobbies (ej: impresión 3D, deportes).
3.  **Sistema de Match:** Mecanismo de conexión dual que habilita canales de coordinación tras la aceptación mutua de una invitación de estudio.
4.  **Sesiones de Estudio Grupal:** Tablón de anuncios para organizar encuentros colectivos en el campus o cafeterías cercanas, permitiendo que otros usuarios se inscriban a sesiones abiertas.

---

## Especificaciones Técnicas
Para garantizar la escalabilidad y el cumplimiento de los requerimientos de la asignatura, el proyecto utiliza el siguiente stack tecnológico:

* **Frontend:** Desarrollado en **JavaScript** utilizando el framework **Next.js** y **React**.
* **Interfaz de Usuario:** Diseño 100% responsive (Móvil, Tablet y Desktop) implementado con la librería **Material UI (MUI)**.
* **Gestión de Datos:** Arquitectura de base de datos **PostgreSQL** utilizando el ORM **Prisma**.
* **Internacionalización:** Soporte nativo multilenguaje (i18n) a medida para Inglés y Español, sin dependencia de APIs externas.
* **Autenticación:** Implementación de **SSO (Single Sign-On)** con gestión de al menos dos roles distintos (Estudiante y Administrador).
* **Infraestructura y DevOps:**
    * **Docker:** Proyecto completamente contenedorizado para asegurar paridad en los entornos de desarrollo con **Hot-reload** activo.
    * **Versionamiento:** Uso estricto de **GitHub** y monitoreo de avances mediante **GitHub Projects**.
    * **Despliegue:** Solución operativa en un proveedor Cloud con URL pública.
* **Estándares de Calidad:** Código fuente escrito íntegramente en inglés siguiendo buenas prácticas de programación.

---

## Documentación del Proyecto
La planificación detallada por Sprints, el levantamiento de requerimientos y otros documentos de diseño se encuentran disponibles en el siguiente enlace:

 **[Acceso a Carpeta de Documentación en Drive: https://drive.google.com/drive/folders/1WjdM_qzehuyMol1MiQYk8Rve7ZjGJrnB?usp=sharing]** 

---

### Guía de Inicio Rápido (Modo Desarrollo)
1.  Clonar el repositorio: `git clone https://github.com/vdukerios/StudyMatch-TICS420`
2.  Configurar variables de entorno en archivo `.env`.
3.  Levantar el entorno con Docker: `docker-compose up --build`
4.  Acceder a la aplicación en: `http://localhost:3000`
