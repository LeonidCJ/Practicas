# Inmobiliaria React - Proyecto Seguro y de Calidad

## Descripción
Aplicación web de gestión inmobiliaria desarrollada en **React.js**, que permite la administración de propiedades, búsqueda y gestión de usuarios.  
El proyecto ha sido adaptado para cumplir con buenas prácticas de **seguridad (OWASP)** y **calidad de procesos (ISO/IEC 12207)**.

La aplicación incluye:
- Gestión de inmuebles (casas, apartamentos, stock)  
- Login seguro con token simulado  
- Rutas públicas y privadas protegidas  
- Validación y sanitización de todos los inputs  
- Lazy loading para componentes y carga optimizada  

---

## Tecnologías
- React.js  
- JavaScript (ES6+)  
- HTML5 / CSS3  
- Bootstrap 5  
- Node.js / npm  
- React Router Dom  
- validator (sanitización de inputs)

---

## Instalación y ejecución
1. Crear archivo .env para variables de entorno

2. Instalar dependencias
npm install

3. Iniciar la aplicación en modo desarrollo:
npm start

4. La app se abrirá en http://localhost:3000

5. En el archivo .env se encuentra el user y contraseña

Completar las variables con los datos de tu entorno local o backend:

REACT_APP_SUPERUSER=admin
REACT_APP_PASSWORD=123
REACT_APP_USERNAME=Administrador
REACT_APP_URL_BASE_FRONTEND=frontend
REACT_APP_API_INMUEBLES=http://localhost:5000/inmuebles
REACT_APP_API_CATEGORIAS=http://localhost:5000/categorias
REACT_APP_API_TIPOS=http://localhost:5000/tipos
REACT_APP_API_ESTADOS=http://localhost:5000/estados
REACT_APP_API_CARACTERISTICAS=http://localhost:5000/caracteristicas
REACT_APP_API_COUNTRIES=http://localhost:5000/countries

