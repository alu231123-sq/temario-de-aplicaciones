# temario-de-aplicaciones
Propósito de Aprendizaje 1
Historia y evolución del desarrollo web: El desarrollo web comenzó con Tim Berners-Lee, quien en 1989 concibió la World Wide Web para facilitar el intercambio de información científica, creando en 1990 el primer navegador, servidor y la propuesta de la web basada en hipertexto (HTML, HTTP, URL). La web evolucionó de ser un sistema estático (Web 1.0) a interactivo y colaborativo (Web 2.0), con la introducción de CSS para el diseño. Posteriormente, con los smartphones y el diseño adaptativo, se dio paso a una experiencia más personalizada y en diversos dispositivos.

Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA):
Las aplicaciones web se clasifican en estáticas (contenido fijo), dinámicas (contenido generado por el servidor y personalizable), Aplicaciones Web de Página Única (SPA) (carga un solo HTML y actualiza contenido sin recargar la página) y Aplicaciones Web Progresivas (PWA) (combinan lo mejor de las apps web y nativas, con funciones como acceso sin conexión y notificaciones push).

2.Arquitectura de aplicaciones web

Cliente-Servidor:La arquitectura cliente-servidor es un modelo informático donde un programa cliente solicita servicios o recursos a un programa servidor, que los provee. El cliente interactúa con el usuario, mientras que el servidor gestiona y centraliza los recursos y el procesamiento de datos. Ejemplos comunes son el uso de un navegador web (cliente) para acceder a sitios web (servidor) o aplicaciones como Netflix. 

Arquitectura de tres capas (presentación, lógica, datos):La arquitectura de tres capas es un patrón de diseño de software que organiza una aplicación en tres capas lógicas: Presentación, Lógica de Negocio (o aplicación) y Datos. Cada capa tiene una responsabilidad específica, lo que facilita la escalabilidad, el mantenimiento y la flexibilidad al separar las preocupaciones dentro del sistema. 

REST y API-first design:REST es un estilo arquitectónico para el diseño de APIs, mientras que un enfoque API-first es una estrategia de desarrollo que prioriza el diseño de la API antes de escribir el código de la aplicación. El diseño API-first asegura la creación de APIs reutilizables y de alta calidad al establecer un contrato claro con los usuarios desde el inicio, alineando a los equipos y utilizando herramientas como la Especificación OpenAPI para la definición y documentación de las APIs. 

3. -Lenguajes y tecnologías fundamentales
HTML, CSS, JavaScript, PHP, MySQL: son tecnologías fundamentales para el desarrollo web. HTML estructura el contenido, CSS define el estilo y la presentación visual, y JavaScript agrega interactividad y dinamismo al sitio. PHP es un lenguaje de programación del lado del servidor que se usa para la lógica de la aplicación y la interacción con bases de datos, mientras que MySQL es un sistema de gestión de bases de datos relacionales para almacenar y recuperar datos de forma eficiente. 

4.-Control de versiones
Git y GitHub:El control de versiones es un sistema para rastrear los cambios en un proyecto a lo largo del tiempo, mientras que Git es una herramienta de control de versiones distribuida que permite gestionar estos cambios localmente. GitHub es una plataforma web que utiliza Git para alojar, gestionar y colaborar en repositorios de código en la nube, facilitando el trabajo en equipo y el respaldo de proyectos. 

Flujo de trabajo con ramas (branching, merge, pull requests):Un flujo de trabajo con ramas en sistemas como GitHub y Git implica crear ramas de funcionalidad aisladas para desarrollar características, luego usar pull requests para proponer y revisar cambios antes de unirlos (merge) a la rama principal. Este proceso asegura que el código pase por revisiones de calidad, previene conflictos y permite la colaboración efectiva en equipos. 

Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web
1.-Diseño e implementación del frontend
Maquetación/Wireframe/Mockup:Una maquetación es el proceso general de organizar y diseñar los elementos de una interfaz, que incluye el wireframe (un esqueleto básico centrado en la estructura y la funcionalidad) y el mockup (una representación visual con colores y tipografía que simula la apariencia final, pero sin interactividad). 

API:Una API (interfaz de programación de aplicaciones) es un conjunto de reglas y definiciones que permite que dos aplicaciones de software diferentes se comuniquen entre sí, actuando como un puente para el intercambio de datos y servicios. Permite a las aplicaciones enviar y recibir información de manera estandarizada, facilitando la creación de aplicaciones más complejas al no tener que desarrollar todas sus funcionalidades desde cero. Por ejemplo, una aplicación de redes sociales usa APIs para obtener tu "feed" de noticias o publicar nuevos contenidos, y una aplicación del clima usa una API para acceder a los datos meteorológicos de otro servicio. 

2.-Diseño e implementación del backend
Servidor:Un servidor es un dispositivo informático potente que, a través de una red (como Internet), proporciona servicios, recursos e información (como archivos, datos o aplicaciones) a otros dispositivos conectados, llamados "clientes". Los servidores están diseñados para manejar y procesar grandes cantidades de datos, así como para atender las solicitudes de múltiples usuarios simultáneamente, siendo fundamentales para aplicaciones como sitios web, correo electrónico y bases de datos. 

Manejo de peticiones y respuestas HTTP:El manejo de peticiones y respuestas HTTP implica la comunicación entre un cliente (como un navegador) y un servidor web, donde el cliente envía un mensaje de petición (con un método como GET o POST) para solicitar o manipular un recurso, y el servidor devuelve un mensaje de respuesta con un código de estado (por ejemplo, 200 OK para éxito o 404 Not Found para error) y opcionalmente datos o un mensaje de error en su cuerpo. Este intercambio de mensajes permite la transferencia de información y el funcionamiento de la web

Conexión a bases de datos (MySQL, PostgreSQL, MongoDB):Una conexión a base de datos permite la comunicación entre un software cliente y un servidor de base de datos, o entre una aplicación y un archivo de base de datos, mediante el envío de comandos y la recepción de datos. Se establece utilizando un conector de datos o una cadena de conexión, que contiene detalles como el tipo de base de datos, la ubicación del servidor y las credenciales de acceso, como el nombre de usuario y la contraseña. 

3.-Bases de datos
 Modelado de datos y relaciones:El modelado de datos es el proceso de crear representaciones visuales que estructuran la información, mostrando cómo se almacenan y las relaciones entre los diferentes puntos de datos, para asegurar que los datos sean consistentes, claros y útiles para el negocio y la toma de decisiones. Las relaciones definen los vínculos lógicos entre las entidades de datos, permitiendo que se pueda recuperar, analizar y relacionar información de manera eficiente en un sistema de información
 
ORM (Object Relational Mapping):Un ORM (Mapeo Objeto-Relacional) es una técnica de programación que actúa como puente entre los lenguajes orientados a objetos y las bases de datos relacionales, traduciendo las clases de código a tablas de base de datos y los objetos a filas de esas tablas. Esto simplifica y agiliza la interacción con las bases de datos, permitiendo a los desarrolladores trabajar con sus objetos de forma más natural en lugar de escribir y gestionar directamente consultas SQL complejas. 

CRUD desde el backend:El CRUD backend se refiere a las cuatro operaciones fundamentales (Crear, Leer, Actualizar y Eliminar) que se implementan en el lado del servidor para gestionar datos. Estas operaciones se realizan sobre las bases de datos y se exponen a través de una API, permitiendo que el frontend (la parte visual de la aplicación) interactúe con la información de forma segura y controlada. 

4.-Seguridad básica en aplicaciones web
Validación de formularios:La seguridad básica en aplicaciones web incluye la validación de formularios para proteger contra ataques de inyección, validación y escaneo de los datos antes de procesarlos. Se deben implementar también medidas de cifrado de datos, como HTTPS, la correcta gestión de contraseñas y la autenticación robusta. Un CAPTCHA es útil para prevenir el acceso automatizado. 

Autenticación y autorización: La autenticación verifica que un usuario sea quien dice ser, mientras que la autorización determina qué acciones o recursos ese usuario puede acceder. En resumen, autenticación es identidad (quién es) y autorización son permisos (qué puede hacer). Ambos son procesos esenciales de seguridad para proteger sistemas e información, trabajando en conjunto para asegurar que solo los usuarios correctos, con los permisos adecuados, puedan acceder a los datos. 

Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional
1. -Integración de frontend y backend
Interfaz de usuario Frontend:La interfaz de usuario (UI) de frontend es la parte de un sitio web o aplicación con la que el usuario interactúa directamente, incluyendo todos los elementos visuales como botones, menús, imágenes y texto. Su propósito es ofrecer una experiencia de usuario intuitiva, accesible y atractiva, utilizando tecnologías como HTML, CSS y JavaScript para crear un diseño coherente y funcional que se adapte a diversos dispositivos y navegadores. 

Manejo de API:El manejo de API es el proceso de interactuar con una interfaz de programación de aplicaciones (API) para intercambiar datos y funcionalidad entre diferentes sistemas de software. Implica hacer solicitudes a un servidor, típicamente a través de métodos HTTP como GET, POST y PUT, usando credenciales como claves de API para obtener acceso autorizado a recursos y procesar las respuestas en formatos como JSON. Herramientas como fetch, Axios, o bibliotecas como React Query facilitan estas interacciones en el desarrollo web, mientras que la gestión completa de las API abarca desde su diseño y protección hasta su monitorización y análisis a lo largo de todo su ciclo de vida. 

Proceso de Solicitud y Respuesta de Backend:El proceso de solicitud y respuesta de backend implica la recepción de una solicitud desde un cliente (frontend) a un servidor de backend a través de HTTP, el procesamiento de datos por parte del backend (validar, ejecutar lógica y consultar la base de datos), y el envío de una respuesta de vuelta al cliente, usualmente en formato JSON o XML, para que se muestre al usuario. 

2.- Almacenamiento en Servidor
Tipos de servidores :Los tipos de servidores varían según su función y la forma en que se alojan o utilizan, incluyendo los servidores web para sitios web, servidores de correo para email, servidores de bases de datos para almacenar datos, servidores proxy como intermediarios, y los servidores virtuales y en la nube que ofrecen flexibilidad y escalabilidad. 

Servidores y servicios de hosting:Los servidores de hosting son computadoras especializadas y la infraestructura física que los proveedores ponen a tu disposición para que tu sitio web, archivos y aplicaciones estén disponibles en Internet. Al contratar un servicio de hosting, básicamente alquilas espacio en un disco duro de uno de estos servidores para almacenar todos los elementos necesarios para que tu web funcione, encargándose el proveedor del mantenimiento, la seguridad y la conexión a la red de forma continua. 

Proveedores de Servicios de Almacenamiento:Los principales proveedores de servicios de almacenamiento, como Google Drive, Microsoft OneDrive, Dropbox, iCloud y MEGA, ofrecen soluciones de almacenamiento en la nube para guardar y acceder a archivos desde cualquier lugar. Estos proveedores varían en sus características, planes de precios (incluyendo versiones gratuitas), integración con otros servicios (como Google Workspace o Microsoft Office) y enfoques en la seguridad. 

3.-Optimización y rendimiento
Optimización de recursos (imágenes, scripts):La optimización de recursos, especialmente de imágenes y scripts, consiste en reducir el tamaño de estos archivos para que una página web cargue más rápido y ofrezca una mejor experiencia al usuario. Esto se logra aplicando técnicas como la compresión de archivos, la selección de formatos modernos (como WebP), el redimensionamiento a las dimensiones adecuadas, y la carga diferida (lazy loading). 

Despliegue de aplicaciones web:El despliegue de aplicaciones web es el proceso de transferir una aplicación desde un entorno de desarrollo a un entorno de producción, haciéndola pública y accesible para los usuarios finales. Este proceso implica la configuración de servidores, bases de datos, la implementación del código, y la implementación de medidas de seguridad y escalabilidad para asegurar la estabilidad y el crecimiento futuro de la aplicación. Es una etapa crítica en el desarrollo de software que permite que el producto pase de ser un proyecto interno a un servicio funcional y disponible en internet. 

CI/CD básico: CI/CD (Integración Continua y Despliegue Continuo) es un conjunto de prácticas y herramientas de DevOps que automatizan el proceso de desarrollo de software, permitiendo a los equipos integrar cambios de código de forma frecuente, probarlos automáticamente y desplegarlos en producción rápidamente y con fiabilidad. Su objetivo es mejorar la calidad del software, reducir el tiempo de comercialización y aumentar la eficiencia del desarrollo mediante la automatización de la compilación, pruebas y despliegues. 

Documentación del proyecto
