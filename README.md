
# 🌐 Nexora - Red Social

> Aplicación web full stack desarrollada como **proyecto integrador** para el bootcamp de desarrollo Java Full Stack en **Generation México**.

---

## 📝 Acerca del Proyecto

**Nexora** es una plataforma de red social diseñada para fomentar la interacción y comunicación continua entre usuarios. Desarrollada con una arquitectura limpia en capas, la aplicación permite a los usuarios registrarse, gestionar su perfil, publicar contenido, interactuar mediante comentarios/reacciones y conectarse con otros miembros en tiempo real.

### Características Principales
- **Autenticación y Autorización de Usuarios:** Registro seguro, inicio de sesión y gestión de sesiones.
- **Gestión de Perfiles:** Perfiles personalizables con biografía, foto de avatar y datos personales.
- **Feed y Publicaciones:** Creación, edición y eliminación de publicaciones de texto y multimedia.
- **Interacciones:** Sistema de me gusta ("likes"), comentarios e interacción con contenido.
- **Diseño Adaptativo (Responsive):** Interfaz limpia e intuitiva optimizada para dispositivos móviles y de escritorio.

---

## 🛠️ Tecnologías Utilizadas

### **Backend**
* **Lenguaje:** Java 17
* **Framework:** Spring Boot
* **Seguridad:** Spring Security / JWT
* **Persistencia:** Spring Data JPA / Hibernate
* **Base de Datos:** MySQL / PostgreSQL

### **Frontend**
* **Core:** JavaScript (ES6+), HTML5, CSS3
* **Estilos y Componentes:** Bootstrap / Tailwind CSS

### **Herramientas y Metodologías**
* **Control de Versiones:** Git & GitHub (Flujo de trabajo GitFlow)
* **Pruebas de API:** Postman / Insomnia
* **Gestión de Proyecto:** Metodología Ágil / Scrum (Jira / Trello)

---

## 🏗️ Arquitectura del Proyecto

El backend sigue una arquitectura limpia orientada a servicios y dividida en capas para garantizar la escalabilidad y el mantenimiento del código:

```text
src/
├── main/
│   ├── java/com/nexora/
│   │   ├── controllers/   # Controladores REST / Endpoints
│   │   ├── services/      # Lógica de Negocio
│   │   ├── repositories/  # Acceso a Datos (JPA Repositories)
│   │   ├── models/        # Entidades y DTOs
│   │   └── config/        # Configuraciones de Seguridad y Aplicación
│   └── resources/          # Archivos de propiedades y recursos estáticos
```

👥 Equipo de Desarrollo
Proyecto desarrollado como trabajo integrador en Generation México:

- Raúl Medina Ortega - Jr. Full Stack Developer - https://www.linkedin.com/in/devraulmedinaortega/
- Mauro Milan - Jr. Full Stack Developer - https://www.linkedin.com/in/ingmauromilan/
- Lizeth Valderrama  - Jr. Full Stack Developer - https://www.linkedin.com/in/lizeth-valderrama-desarrolladorajr/
- Paulina Cruz  - Jr. Full Stack Developer -  https://www.linkedin.com/in/paulina-cruz-mx/
- Valeria Pérez  - Jr. Full Stack Developer  - https://www.linkedin.com/in/valeria-perez-iq/
- Uriel Diaz - Jr. Full Stack Developer - https://www.linkedin.com/in/urieldiazdesarrollador/
- Leonardo Hernández  - Jr. Full Stack Developer - https://www.linkedin.com/in/leo-hernandez-c/


📄 Licencia

Este proyecto fue realizado con fines educativos como parte del programa de formación en Generation México.
