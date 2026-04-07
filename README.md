# StudyMatch: Descubrimiento de Pares Académicos

## Información Institucional
* [cite_start]**Universidad:** Universidad Adolfo Ibáñez[cite: 3].
* **Facultad:** Facultad de Ingeniería y Ciencias.
* [cite_start]**Curso:** Programación Profesional (TICS420-1-2026)[cite: 1, 30].
* [cite_start]**Docentes:** Nicolás Cenzano, Nicolás Escobar, Cristóbal Quijanes[cite: 28].

## Integrantes
* **Integrante 1:** Valentín Duke.
* **Integrante 2:** Fernanda Quiros.

---

## Propuesta de Valor (The Pitch)
[cite_start]El modelo educativo actual exige una alta carga de trabajo autónomo, estimada en al menos 3 horas de estudio fuera de clases por cada hora cronológica en el aula[cite: 304]. [cite_start]Sin embargo, la mayoría de los estudiantes enfrentan este desafío de manera aislada debido a la "Inercia Social" y la falta de afinidad con sus pares académicos[cite: 305, 306].

[cite_start]**StudyMatch** es una plataforma de descubrimiento de pares diseñada para conectar a estudiantes de la UAI que cursan los mismos ramos y buscan compañeros con quienes no solo estudiar, sino también generar afinidad personal[cite: 310]. [cite_start]Al integrar habilidades técnicas con intereses personales como hobbies o proyectos, eliminamos la fricción de "acercarse a un extraño" y transformamos el estudio en una instancia de colaboración social segura y validada por el correo institucional[cite: 311, 312, 318].

---

## Lógica del Negocio
La plataforma gestiona el ciclo de vida del estudio colaborativo mediante las siguientes funcionalidades clave:

1.  [cite_start]**Perfil de Afinidad Académica:** Registro de ramos vigentes, carrera y un desglose de fortalezas académicas (ej: "Finanzas" o "React")[cite: 315].
2.  [cite_start]**Discovery Basado en Intereses:** Interfaz para explorar perfiles de otros alumnos filtrando por necesidad académica y compatibilidad de estilos o hobbies (ej: impresión 3D, deportes)[cite: 316, 317].
3.  [cite_start]**Sistema de Match:** Mecanismo de conexión dual que habilita canales de coordinación tras la aceptación mutua de una invitación de estudio[cite: 318].
4.  [cite_start]**Sesiones de Estudio Grupal:** Tablón de anuncios para organizar encuentros colectivos en el campus o cafeterías cercanas, permitiendo que otros usuarios se inscriban a sesiones abiertas[cite: 318].

---

## Especificaciones Técnicas
[cite_start]Para garantizar la escalabilidad y el cumplimiento de los requerimientos de la asignatura[cite: 14], el proyecto utiliza el siguiente stack tecnológico:

* [cite_start]**Frontend:** Desarrollado en **JavaScript** utilizando el framework **Next.js** y **React**[cite: 16].
* [cite_start]**Interfaz de Usuario:** Diseño 100% responsive (Móvil, Tablet y Desktop) implementado con la librería **Material UI (MUI)**[cite: 17, 35].
* **Gestión de Datos:** Arquitectura de base de datos **PostgreSQL** utilizando el ORM **Prisma**.
* [cite_start]**Internacionalización:** Soporte nativo multilenguaje (i18n) a medida para Inglés y Español, sin dependencia de APIs externas[cite: 18, 35].
* [cite_start]**Autenticación:** Implementación de **SSO (Single Sign-On)** con gestión de al menos dos roles distintos (Estudiante y Administrador)[cite: 18, 34].
* **Infraestructura y DevOps:**
    * **Docker:** Proyecto completamente contenedorizado para asegurar paridad en los entornos de desarrollo con **Hot-reload** activo.
    * [cite_start]**Versionamiento:** Uso estricto de **GitHub** y monitoreo de avances mediante **GitHub Projects**[cite: 20].
    * [cite_start]**Despliegue:** Solución operativa en un proveedor Cloud con URL pública[cite: 23].
* [cite_start]**Estándares de Calidad:** Código fuente escrito íntegramente en inglés siguiendo buenas prácticas de programación[cite: 21].

---

## Documentación del Proyecto
La planificación detallada por Sprints, el levantamiento de requerimientos y otros documentos de diseño se encuentran disponibles en el siguiente enlace:

📂 **[Acceso a Carpeta de Documentación en Drive](#)** *(Reemplazar con el link real)*

---

### Guía de Inicio Rápido (Modo Desarrollo)
1.  Clonar el repositorio: `git clone [url-del-repo]`
2.  Configurar variables de entorno en archivo `.env`.
3.  Levantar el entorno con Docker: `docker-compose up --build`
4.  Acceder a la aplicación en: `http://localhost:3000`
