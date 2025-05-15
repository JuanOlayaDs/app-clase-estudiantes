<h1 align="left">🎓 App Clase Estudiantes</h1>

###

<p align="left">Es una aplicación web creada con el objetivo de facilitar el registro, visualización y administración de calificaciones de estudiantes. Fue diseñada como proyecto académico para demostrar el uso de rutas protegidas, autenticación, enrutamiento entre componentes y manejo de interfaz amigable en una SPA (Single Page Application).</p>

###

<h1 align="left">🖊️ Descripción</h1>

###

<p align="left">La aplicación permite a los usuarios iniciar sesión y acceder a diversas secciones informativas, como Inicio, Servicios, Contacto y Acerca de, mediante un menú de navegación lateral. Además, incorpora rutas privadas para proteger el contenido interno. La aplicación está conectada a una base de datos, lo que permite gestionar de manera real el flujo de autenticación, el almacenamiento de calificaciones y la navegación en un entorno educativo web.</p>

###

<h2 align="left">🛠️ Tecnologías Utilizadas</h2>

###

<p align="left">React JS: Librería principal para la construcción de interfaces.<br><br>React Router DOM: Manejo de rutas internas y navegación SPA.<br><br>CSS: Estilos personalizados para cada componente.<br><br>HTML5: Estructura base del proyecto.<br><br>JavaScript (ES6+): Lógica de funcionalidad en el frontend.<br><br>Vite: Entorno de desarrollo rápido para aplicaciones React.</p>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="nodejs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/npm/npm-original-wordmark.svg" height="40" alt="npm logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  />
</div>

###

<h2 align="left">🎨 Paleta de colores</h2>

###

<p align="left">#244855 (azul académico)<br><br>#2C6E49 (verde educativo)<br><br>#F5F5F5 (gris claro)<br><br>#E8E8E8 (gris interfaz)<br><br>#C5283D (rojo acento)</p>

###

<h2 align="left">📃 Tipografías</h2>

###

<p align="left">Poppins: Títulos y encabezados.<br><br>Roboto: Texto general y formularios.</p>

###

<h2 align="left">🚀 Ejecución del proyecto</h2>

###

<p align="left">Frontend: Vite + ReactURL por defecto: http://localhost:5173</p>

###

<h2 align="left">📁 Estructura del proyecto</h2>

###

<p align="left">app-clase-estudiantes/<br>├── public/                    # Imágenes y archivos estáticos<br>├── src/<br>│   ├── components/            # Componentes reutilizables (MenuLateral, RutaProtegida)<br>│   ├── pages/                 # Páginas principales (Home, Login, Servicios, Contacto, Acerca)<br>│   ├── router/                # Enrutador con React Router<br>│   ├── services/              # Simulación de base de datos<br>│   └── main.jsx               # Punto de entrada de la app<br>├── index.html<br>├── package.json<br>└── vite.config.js</p>

###

<h2 align="left">📓 Pasos de Desarrollo</h2>

###

<p align="left">Inicialización del proyecto con Vite y configuración básica.<br><br>Creación del formulario de login.<br><br>Desarrollo de las páginas: Home, Servicios, Contacto, Acerca.<br><br>Implementación de React Router para el enrutamiento.<br><br>Desarrollo del componente RutaProtegida para proteger vistas.<br><br>Inclusión del menú lateral persistente con MenuLateral.<br><br>Incorporación de estilos CSS personalizados y fondos visuales.<br><br>Simulación de datos de usuarios para validación.<br><br>Pruebas funcionales y ajustes finales.<br><br>Documentación y despliegue en GitHub.</p>

###

<h2 align="left">📊 Modelo de datos (Simulado):</h2>

###

<p align="left">La lógica de autenticación y almacenamiento se realiza en el archivo:<br><br>src/services/dataBase.js</p>

###

<h1 align="left"></h1>

###

<p align="left">{<br>        id: 1,<br>        email: "juan.perez@example.com",<br>        name: "Juan Perez",<br>        password: "hashed_password_123",<br>        phone_number: "+525511223344",<br>        user_type: "teacher"<br>    },<br>    {<br>        id: 2,<br>        email: "maria.garcia@example.com",<br>        name: "Maria Garcia",<br>        password: "hashed_password_456",<br>        phone_number: "+525566778899",<br>        user_type: "student"<br>    },<br>    {<br>        id: 3,<br>        email: "carlos.lopez@example.com",<br>        name: "Carlos Lopez",<br>        password: "hashed_password_789",<br>        phone_number: "+525512345678",<br>        user_type: "teacher"<br>    },<br>    {<br>        id: 4,<br>        email: "ana.martinez@example.com",<br>        name: "Ana Martinez",<br>        password: "hashed_password_101",<br>        phone_number: "+525598765432",<br>        user_type: "student"<br>    },<br>    {<br>        id: 5,<br>        email: "luis.ramirez@example.com",<br>        name: "Luis Ramirez",<br>        password: "hashed_password_202",<br>        phone_number: "+525576543210",<br>        user_type: "student"<br>    },<br>    {<br>        id: 6,<br>        email: "sofia.gomez@example.com",<br>        name: "Sofia Gomez",<br>        password: "hashed_password_303",<br>        phone_number: "+525534567890",<br>        user_type: "teacher"<br>    },<br>    {<br>        id: 7,<br>        email: "diego.morales@example.com",<br>        name: "Diego Morales",<br>        password: "hashed_password_404",<br>        phone_number: "+525523456789",<br>        user_type: "student"<br>    },<br>    {<br>        id: 8,<br>        email: "valeria.nunez@example.com",<br>        name: "Valeria Nunez",<br>        password: "hashed_password_505",<br>        phone_number: "+525578912345",<br>        user_type: "teacher"<br>    }</p>

###

<h2 align="left"></h2>

###

<p align="left"></p>

###

<h2 align="left"></h2>

###

<div align="left">
</div>

###

###

<h2 align="left">🧪 Funcionalidades Implementadas</h2>

###

<p align="left">✔️ Inicio de sesión con verificación local.<br><br>✔️ Redirección automática de rutas protegidas si no hay sesión activa.<br><br>✔️ Visualización de lista de estudiantes (nombre, documento, nota).<br><br>✔️ Cierre de sesión y retorno a login.<br><br>✔️ Navegación lateral visible tras autenticación.<br><br>✔️ Estructura de componentes modular y reutilizable.</p>

###

<h2 align="left">🤝 Autores</h2>

###

<p align="left">Proyecto desarrollado por estudiantes del programa Frontend II:<br><br>Christian Ramos Arias,<br><br>Juan Felipe Moreno Cataño,<br><br>Santiago Gómez Barrientos,<br><br>Esteban Felipe Galvis Londoño<br><br>y Juan Camilo Olaya Herrera.</p>

###