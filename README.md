# 🌟 Sistema de Gestión de Tareas Personales 🌟

## 📝 Descripción del Proyecto

🎯 **Objetivo**: Desarrollar una aplicación en **Python** con una base de datos en **MySQL** que permita a los usuarios gestionar sus tareas personales de manera eficiente. La aplicación incluirá:

- ✅ **Sistema CRUD**: Crear, Leer, Actualizar y Eliminar tareas.
- 🚀 Funcionalidades robustas:
  - Manejo de excepciones para errores comunes.
  - Interacción amigable y dinámica con el usuario.
- 🛠️ Herramientas adicionales: uso de estructuras condicionales y ciclos iterativos.

📊 **Base de datos**: La estructura será gestionada en **phpMyAdmin**, y se incluirá una captura de pantalla de su descripción.

✨ Al final, el sistema proporcionará una solución sencilla y eficiente para organizar tareas, garantizando que los usuarios tengan una experiencia fluida y sin contratiempos.

---

## 🔧 Pasos para el Desarrollo

### 1️⃣ **Diseño de la Base de Datos**

📂 Se creará una tabla llamada `tareas` con la siguiente estructura:

| 🆔 Campo         | 🔢 Tipo            | 📜 Detalles                                 |
|------------------|-------------------|--------------------------------------------|
| `id`            | INT               | Clave primaria, Auto_increment             |
| `titulo`        | VARCHAR(255)      | No nulo                                    |
| `descripcion`   | TEXT              | Opcional                                   |
| `fecha_limite`  | DATE              | Opcional                                   |
| `estado`        | ENUM              | Valores: 'pendiente', 'completado', por defecto: 'pendiente' |

📸 **Captura Ejemplo de la Tabla en phpMyAdmin:**

![phpMyAdmin tabla tareas](https://via.placeholder.com/600x300?text=Captura+de+phpMyAdmin)

---

### 2️⃣ **Funcionalidades del Código en Python**

🖥️ La aplicación implementará las siguientes funcionalidades interactivas:

- **🆕 Crear**: Añadir nuevas tareas.
- **📋 Leer**: Mostrar la lista de tareas con filtros opcionales (por ejemplo, solo pendientes).
- **🛠️ Actualizar**: Modificar el título, descripción, fecha límite o estado de una tarea existente.
- **❌ Eliminar**: Borrar tareas específicas usando su ID.

📚 **Detalles Técnicos**:

- 🛡️ **Manejo de Excepciones**: Gestión de errores como:
  - Conexión fallida con la base de datos.
  - Entradas inválidas por parte del usuario.
- 🔄 **Estructuras Condicionales y Iterativas**:
  - Navegación por opciones del menú principal.
  - Mantener la aplicación activa hasta que el usuario elija salir.

### 🛠️ **Diagrama de Flujo**

¡Un vistazo a cómo funcionará la aplicación! 🖼️

![Diagrama de Flujo](https://via.placeholder.com/600x300?text=Diagrama+de+Flujo)

---

## 📦 Formato de Entrega

1️⃣ **PDF**:

- Incluir:
  - ✍️ La descripción del proyecto.
  - 📸 Una captura de la tabla `tareas` en phpMyAdmin.

2️⃣ **Código ZIP**:

- Adjuntar:
  - 🗂️ Los archivos `.py` del proyecto.
  - 📜 Un archivo `README.md` con instrucciones para ejecutar el programa.

---

💡 **¿Listos para construirlo?** ¡Vamos a crear algo increíble juntos! 🚀
