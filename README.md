# Proyecto: Firebase-Lista de Alumnos
Este proyecto es una aplicación web básica que utiliza Firebase Authentication y Firebase Firestore
para permitir el registro, inicio de sesión y gestión de una lista de alumnos.
## Características
- Registro e inicio de sesión de usuarios con Firebase Authentication.
- Almacenamiento de información de alumnos (nombre, carrera, edad, materias) en Firestore.
- Visualización y carga dinámica de alumnos solo si el usuario está autenticado.
- Interfaz responsiva y clara.
## Tecnologías utilizadas
- HTML5, CSS3, JavaScript
- Firebase (Auth, Firestore)
- Firebase SDK versión compat (compatibilidad)
## Estructura del proyecto
- `index.html`: Interfaz principal del usuario.
- `style.css`: Estilos visuales.
- `script.js`: Lógica de autenticación y comunicación con Firestore.
- `README.md`: Información general del proyecto.
## Configuración
1. Crea un proyecto en [Firebase Console](https://console.firebase.google.com/).
2. Habilita Firebase Authentication (con Email/Password).
3. Crea una base de datos Firestore.
4. Copia y pega tu configuración Firebase en la sección `firebaseConfig` dentro de `script.js`.
5. Asegúrate de que la colección `alumnos` exista o sea creada desde la interfaz.
## Notas
- Este proyecto es solo un ejemplo educativo. No está optimizado para producción.
- Asegúrate de configurar las reglas de seguridad de Firestore adecuadamente.
