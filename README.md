🚘 Sistema de Gestión de Vehículos

🌐 Aplicación web moderna para la gestión de vehículos, desarrollada por Alejandro Benítez.
Permite registrar, visualizar, actualizar y eliminar información de vehículos de forma dinámica y ordenada.

Este documento explica la estructura del código, el paso a paso para ejecutar el proyecto, y la manera de agregar evidencias de funcionamiento de la aplicación.

🧩 Tecnologías utilizadas

Tipo	Tecnología

Lenguaje principal	JavaScript (ES6+)

Framework / Librería	React.js

Bundler	Vite

Estilos	CSS3 / TailwindCSS

Gestión de dependencias	npm

Control de versiones	Git + GitHub

📁 Estructura del proyecto

/vehiculos-front/
├── public/ → Archivos estáticos (favicon, index.html)
├── src/
│ ├── assets/ → Imágenes e íconos
│ ├── components/ → Componentes reutilizables (Navbar, Formulario, TablaVehículos, etc.)
│ ├── pages/ → Vistas principales (Home, Vehículos, Registro, etc.)
│ ├── services/ → Conexión con API (GET, POST, PUT, DELETE)
│ ├── App.jsx → Estructura principal de la aplicación
│ ├── main.jsx → Punto de entrada (monta la app en el DOM)
│ └── index.css → Estilos globales
├── package.json → Dependencias y scripts
├── vite.config.js → Configuración del entorno
└── README.md → Este documento

📘 Principales componentes:

FormularioVehiculo.jsx → Formulario para agregar o editar información de un vehículo.

TablaVehiculos.jsx → Tabla dinámica con todos los vehículos registrados.

🧠 Funcionalidades principales

Funcionalidad	Descripción

📋 Listar vehículos	Muestra todos los vehículos registrados en el sistema.

➕ Registrar vehículo	Permite agregar un nuevo vehículo a la base de datos.

✏️ Editar vehículo	Modifica los datos de un vehículo existente.

❌ Eliminar vehículo	Elimina un vehículo del registro.

🔍 Buscar vehículo	Busca por placa, marca o modelo.

Todas las funciones se comunican con un backend mediante peticiones REST (GET, POST, PUT, DELETE).

EVIDENCIAS DE FUNCIONAMIENTO 
CREAR UN VEHICULO 
<img width="1919" height="1079" alt="Captura de pantalla 2025-11-06 104319" src="https://github.com/user-attachments/assets/9d646763-fe30-488c-8470-f5cdad6bfb09" />

LISTAR TODOS LOS VEHICULOS 

<img width="1919" height="1079" alt="Captura de pantalla 2025-11-06 104826" src="https://github.com/user-attachments/assets/430ad7f6-629a-4223-9ed8-84a8f196f101" />

EDITAR UN VEHICULO 

<img width="1918" height="1079" alt="Captura de pantalla 2025-11-06 105616(1)(1)" src="https://github.com/user-attachments/assets/1c5f0844-82ae-4207-828e-644ba9520e80" />

ELIMINAR UN VEHICULO 

<img width="1919" height="1077" alt="Captura de pantalla 2025-11-06 105630" src="https://github.com/user-attachments/assets/058331ec-25a5-43ef-8d80-3070eb1defe9" />

CREAR UNA MOTO 

<img width="1918" height="1079" alt="Captura de pantalla 2025-11-06 104928" src="https://github.com/user-attachments/assets/6be69b3f-82f5-40b3-b805-249333fff95d" />

LISTAR TODAS LAS MOTOS 

<img width="1912" height="1078" alt="Captura de pantalla 2025-11-06 105139" src="https://github.com/user-attachments/assets/7576b91f-a56c-44a5-abf1-b1fd2489c718" />

EDITAR UNA MOTO

<img width="1905" height="1075" alt="Captura de pantalla 2025-11-06 105504(1)(1)" src="https://github.com/user-attachments/assets/5e3582fa-c6d1-4e57-a673-752d1d399ee2" />

ELIMINAR UNA MOTO 

<img width="1918" height="1079" alt="Captura de pantalla 2025-11-06 105542" src="https://github.com/user-attachments/assets/07d5f17b-bb26-4559-8167-2a847bf781b4" />



👨‍💻 Autor

Desarrollado por: Alejandro Benítez
