# Capítulo IV: Product Design

## 4.1. StyleGuidelines

### 4.1.1. General Style Guidelines.

En este apartado, se mostrará de manera organizada los estilos y herramientas que se usarán para diseñar nuestra solución.

### 4.1.2. Web Style Guidelines

Descripción de la Startup:
VerSoft, una startup formada por cinco estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC), está dedicada a crear una solución innovadora para la gestión de inventarios en el sector gastronómico. Su plataforma, llamada FoodOS, tiene como objetivo principal optimizar y simplificar los procesos de inventario en restaurantes. Desde el seguimiento de existencias hasta la gestión de proveedores y el análisis predictivo de datos, FoodOS divide y optimiza los procesos esenciales del inventario de los restaurantes. VerSoft se compromete a proporcionar una aplicación web poderosa y fácil de usar para revolucionar la documentación y optimización de estos procesos clave.
Misión:
FoodOS proporcionará una solución tecnológica avanzada para redefinir la gestión de inventarios en el sector gastronómico.
Visión:
En los próximos años, VerSoft se destacará como un modelo de negocio comprometido con la gestión de inventarios y se convertirá en la plataforma líder en gestión de inventarios para restaurantes.

![Usuario](/Assets/Img/Chapter%20IV/VerSoftLogo.png)

Por otro lado, La propuesta para el branding que utilizaremos será FoodOS en el siguiente modelo: 

![Usuario](/Assets/Img/Chapter%20IV/FoodOSLogo.png)

Colors:

Los colores juegan un papel fundamental en la primera impresión visual de los usuarios. Basándonos en los principios de la psicología del color, hemos elegido una paleta cromática en la que el verde, el marrón y el amarillo desempeñan roles prominentes en la implementación de nuestra plataforma.

El color verde se ha seleccionado como la tonalidad principal de nuestra paleta cromática. El verde simboliza equilibrio, crecimiento y prestigio, tres elementos fundamentales que buscamos transmitir como parte de la identidad de nuestra startup. Además, el verde está estrechamente asociado con la naturaleza y la agricultura, reflejando el enfoque de nuestra plataforma hacia el sector agropecuario. Asimismo, el verde evoca el concepto de armonía, que es uno de los pilares que queremos ofrecer a nuestros usuarios durante su interacción con nuestro servicio.

Como tonalidades secundarias, complementamos el verde con variedades cromáticas del marrón y el amarillo. El marrón transmite estabilidad, confianza y robustez, cualidades que refuerzan la fiabilidad y solidez de nuestra plataforma. Por otro lado, el amarillo aporta energía, vitalidad y optimismo, lo que se alinea con nuestra visión de proporcionar una experiencia dinámica y positiva a nuestros usuarios.

En conjunto, la combinación de verde, marrón y amarillo en nuestra paleta cromática refleja la identidad, valores y objetivos de nuestra startup, creando una experiencia visual atractiva y coherente para nuestros usuarios.

paleta de colores de FoodOS:
![Usuario](/Assets/Img/Chapter%20IV/PaletadecoloresdeFoodOS.png)
paleta de colores de VerSOFT
![Usuario](/Assets/Img/Chapter%20IV/Paletadecoloresdeversfot.png)

## 4.2. Information Architecture

### 4.2.1. Organization Systems

A Continuación, se indican los tipos de estructura visual que tendrá cada grupo de información con respecto al segmento objetivo y al tipo de categorización que se usará.

### 4.2.2. Labeling Systems


### 4.2.3. SEO Tags and Meta Tags


### 4.3.1. Landing Page Wireframe

### 4.4.2. Web Application Wireflow Diagrams

### 4.4.3. Web Application Mock-ups

### 4.4.4. Web Application User Flow Diagram

## 4.5. Web Applications Prototyping
En esta sección se mostrará el prototipo de la aplicación web desarrollado en figma siguiendo los estilos establecidos en los anteriores puntos.
[Link: Visualizar Prototipo en Figma](https://www.figma.com/proto/9U0r61ZoDHjQf7Ck7zotUL/Prototype-TecHelp-APP?type=design&node-id=1-3234&t=HruT40GoBdMnazGq-1&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=1%3A3234&show-proto-sidebar=1&mode=design )

![captura]()

## 4.6 Domain-Driven Software Architecture

Los diagramas de arquitectura de software nos ayudan a plantear el sistema de nuestro software, basándonos en el enfoque de desarrollo de Domain Driven Design.
### 4.6.1. Software Architecture Context Diagram.
![Diagrama de Contexto](/Assets/Img/Chapter%20IV/structurizr-SystemContext-001.png)

### 4.6.2. Software Architecture Container Diagrams.
![Diagram Container](/Assets/Img/Chapter%20IV/structurizr-Container-001.png)


### 4.6.3. Software Architecture Components Diagrams.
![Diagrama de Componentes](/Assets/Img/Chapter%20IV/structurizr-Componente.png)

![Diagrama de Componentes](/Assets/Img/Chapter%20IV/structurizr-WebApp.png)


## 4.7 Software Object-Oriented Design
### 4.7.1. Class Diagrams.

![imagen](/Assets/Img/Chapter%20IV/Blank%20diagram%20(5).png)
<center>

[Link de lucid del diagrama de clases](https://lucid.app/lucidchart/4ef87a5e-db0e-4cf2-b181-134d58fce7f4/edit?viewport_loc=-980%2C-723%2C5424%2C2574%2C0_0&invitationId=inv_fa3364c0-52d8-4abe-bd56-bd5a87f86986)

</center>

### 4.7.2. Class Dictionary
En esta sección se mostrará el diccionario de las clases, usado para el desarrollo de nuestra app.

* __Profile:__ Clase que contiene los atributos del perfil como dirreccion, email y la foto.
* __Email:__ Clase que contiene el email.
* __PersonName:__ Clase que contiene los atributos de nombres y apellidos.

* __Product:__ Clase que contiene  los atributos de los productos como nombre,fecha de vencimiento y estado
* __DateProduct:__ Clase que contiene las fechas del producto.

* __ProfileComandService:__ Clase que contiene las funciones para ingresar o actualizar datos en las base de datos
* __ProfileQueryService__ Clase que contiene las funciones para realizar consultas a la base de datos

* __ProductComandService:__ Clase que contiene las funciones para ingresar o actualizar datos en las base de datos
* __ProductQueryService:__ Clase que contiene las funciones para realizar consultas a la base de datos

* __InventoryController:__ Clase que contiene las funciones con los verbos del api para realizar las diversas peticiones.
* __ProfileControler:__ Clase que contiene las funciones con los verbos del api para realizar las diversas peticiones.


## 4.8. Database Design.
### 4.8.1. Database Diagram

A continuacion se presentará nuestro Physical data model desarrollado en vertabelo.

![Diagrama Base de datos](/Assets/Img/Chapter%20IV/foodOs-2024-04-09_23-52.png)

[Link para visualizar el diagrama de base de datos](https://my.vertabelo.com/doc/XvR35ZlxiJYY3qqEmS4yOWgxLK9KMufB)
