# My Landing Page

My Landing Page es una página web sencilla creada con React. Incluye un sistema de enrutamiento usando `react-router-dom` que permite navegar entre al menos dos vistas secundarias.

## Requisitos

- Node.js (versión 18 recomendada)
- npm o yarn

## Instalación

1. **Clonar el repositorio**:
   git clone https://github.com/tu-usuario/my-landing-page.git
   cd my-landing-page

2. **Instalar dependencias**:
   npm install

3. **Instalar `react-router-dom`**:

   npm install react-router-dom


## Uso

1. **Iniciar la aplicación**:

   npm start


   La aplicación se iniciará en `http://localhost:3000`.

## Estructura del Proyecto


my-landing-page/
├── node_modules/
├── public/
├── src/
│   ├── components/
│   │   ├── About.js
│   │   ├── Contact.js
│   │   ├── Home.js
│   │   ├── Navbar.js
│   ├── App.css
│   ├── App.js
│   ├── index.js
├── package.json
├── package-lock.json
└── README.md


## Descripción de Archivos

- **App.js**: Contiene la configuración principal de la aplicación, incluyendo la navegación.
- **index.js**: Punto de entrada de la aplicación.
- **About.js**: Componente de la vista "About".
- **Contact.js**: Componente de la vista "Contact".
- **Home.js**: Componente de la vista "Home".
- **Navbar.js**: Componente de la barra de navegación.
- **App.css**: Contiene los estilos CSS para la aplicación.
- **package.json**: Contiene las dependencias y scripts del proyecto.

## Contribuir

1. **Fork** el repositorio
2. **Clonar** tu fork:

   git clone https://github.com/tu-usuario/my-landing-page.git

3. **Crear una rama** para tu feature:

   git checkout -b mi-nueva-feature

4. **Hacer commit** de tus cambios:

   git commit -m 'Añadir nueva feature'

5. **Hacer push** a la rama:

   git push origin mi-nueva-feature

6. **Crear un Pull Request**
