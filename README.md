# ACME AIR - Maquetación de Interfaz Web Móvil

Este proyecto consiste en la maquetación (HTML + CSS) de la nueva interfaz de usuario de la aplicación web móvil de **ACME AIR**, basada en las vistas diseñadas por el departamento de **UI/UX**.

---

## 📱 Objetivo del Proyecto

Desarrollar las páginas web (HTML + CSS) adaptando las vistas proporcionadas por el equipo de diseño. Los elementos deben ser **responsivos**, es decir, adaptarse correctamente al ancho de la pantalla en dispositivos móviles, siguiendo el diseño provisto en las imágenes entregadas.

---

## 🧩 Requerimientos Funcionales

Cada botón o enlace dentro de la aplicación debe redirigir correctamente a su respectiva vista. A continuación se describe el flujo de navegación entre vistas:

### 🗺️ Flujo de Navegación

| Vista Origen                          | Acción / Enlace                     | Vista Destino                  |
|--------------------------------------|-------------------------------------|--------------------------------|
| **Login**                            | Ingresar                            | Menú "¿Qué quieres hacer?"     |
| **Login**                            | Crear cuenta                        | Registro                       |
| **Login**                            | ¿Has olvidado tu contraseña?        | Recuperar contraseña           |
| **Registro**                         | Guardar                             | Crear Contraseña               |
| **Recuperar contraseña**             | Enviar                              | Crear Contraseña               |
| **Crear contraseña**                 | Guardar                             | Menú "¿Qué quieres hacer?"     |
| **Menú "¿Qué quieres hacer?"**       | Cerrar sesión                       | Login                          |
| **Menú "¿Qué quieres hacer?"**       | Buscar vuelos                       | Búsqueda de vuelos             |
| **Búsqueda de vuelos**               | Buscar                              | Vuelos disponibles             |
| **Vuelos disponibles**               | Volver                              | Menú "¿Qué quieres hacer?"     |
| **Menú "¿Qué quieres hacer?"**       | Check-In                            | Check-In                       |
| **Check-In**                         | Guardar                             | Menú "¿Qué quieres hacer?"     |
| **Menú "¿Qué quieres hacer?"**       | Mis vuelos                          | Mis vuelos                     |
| **Mis vuelos**                       | Volver                              | Menú "¿Qué quieres hacer?"     |

> **Nota:** Todas las vistas que incluyan la opción **"Cerrar sesión"** deben redirigir al **Login**.

---

## 🛠️ Tecnologías Utilizadas

- HTML5
- CSS3 (sin frameworks)
- Responsive Design (mobile-first)

---

## 📂 Estructura del Proyecto

```
acme-air/
├── index.html (Login)
├── registro.html
├── recuperar-contraseña.html
├── crear-contraseña.html
├── menu.html
├── buscar-vuelos.html
├── vuelos-disponibles.html
├── check-in.html
├── mis-vuelos.html
├── css/
│   └── estilos.css
└── assets/
    └── imágenes/
```

---

## 📄 Github Page

https://carlosvillamizar09.github.io/Proyecto-Aerolinea/index.html

---
## 👨‍💻 Autor

Desarrollado por **@Carlosvillamizar09** como parte del proyecto de renovación de interfaz para ACME AIR.
