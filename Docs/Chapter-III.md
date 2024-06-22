# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping 

![Usuario](/Assets/Img/Chapter%20III/Tobe%20Escenario%20Mapping.jpg)


## 3.2. User Stories

| Epic/storie Id | Título                                             | Descripción                                                                                      | Criterio de aceptación                                                    | Epic |
|----------------|----------------------------------------------------|--------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|------|
| US01           | Registro de cuenta                                | Como usuario, quiero crear una cuenta para ingresar a la aplicación.                             | **Escenario 1:** Registro correcto                                       | 1    |
|                |                                                    |                                                                                                  | **Escenario 2:** Registro incorrecto                                     |      |
| US02           | Inicio de sesión                                  | Como usuario, quiero iniciar sesión con mi cuenta creada.                                         | **Escenario 1:** Inicio de sesión correcto                               | 1    |
|                |                                                    |                                                                                                  | **Escenario 2:** Inicio de sesión incorrecta                             |      |
| US03           | Cierre de sesión                                  | Como usuario, quiero poder cerrar mi sesión en la aplicación.                                      | **Escenario 1:** Cierre correcto de la sesión                            | 1    |
| US04           | Actualizar información de cuenta                  | Como usuario, quiero mantener mi información de mi perfil actualizada.                            | **Escenario 1:** Cambio correcto de la información                       | 2    |
|                |                                                    |                                                                                                  | **Escenario 2:** Cambio incorrecto de la información                     |      |
| US05           | Visualizar información de la cuenta               | Como usuario, quiero poder visualizar la información de mi cuenta para verificarla.               | **Escenario 1:** Visualización correcta de la información                | 2    |
|                |                                                    |                                                                                                  | **Escenario 2:** No se visualiza nada de la información                  |      |
| US06           | Eliminar permanentemente la cuenta                | Como usuario, quiero eliminar mi cuenta al no querer usar más la app.                              | **Escenario 1:** Eliminación correctamente del perfil                    | 2    |
|                |                                                    |                                                                                                  | **Escenario 2:** Eliminación incorrectamente del perfil                  |      |
| US07           | Agregar un producto al inventario                 | Como usuario, quiero agregar un producto a mi inventario.                                          | **Escenario 1:** Usuario agrega un producto al inventario correctamente | 3    |
|                |                                                    |                                                                                                  | **Escenario 2:** Usuario agrega un producto al inventario incorrectamente|      |
| US08           | Eliminar un producto al inventario                | Como usuario, quiero eliminar un producto de mi inventario.                                         | **Escenario 1:** Usuario elimina un producto del inventario correctamente| 3    |
|                |                                                    |                                                                                                  | **Escenario 2:** Usuario elimina un producto por error                   |      |
| US09           | Actualizar un producto al inventario              | Como usuario, quiero actualizar los datos de un producto.                                          | **Escenario 1:** El usuario actualiza datos del producto correctamente  | 3    |
|                |                                                    |                                                                                                  | **Escenario 2:** El usuario actualiza datos del producto incorrectamente|      |
| US10           | Ver todos los productos del inventario            | Como usuario, quiero ver todos los productos del almacén.                                          | **Escenario 1:** El usuario visualiza correctamente los productos de su inventario| 3    |
|                |                                                    |                                                                                                  | **Escenario 2:** El usuario no visualiza correctamente los productos de su inventario|      |
| US11           | Poder ver los productos prontos a vencer         | Como usuario, quiero poder ver los productos que estén a punto de vencer para poder aprovecharlos en la producción.| **Escenario 1:** El usuario visualiza los productos más cercanos a vencer | 3    |
|                |                                                    |                                                                                                  | **Escenario 2:** El usuario no visualiza los productos más cercanos a vencer|      |
| US12           | Obtener información sobre los proveedores         | Como usuario, quiero ver los proveedores de cierto producto.                                        | **Escenario 1:** El usuario obtiene información de sus proveedores      | 4    |
|                |                                                    |                                                                                                  | **Escenario 2:** El usuario no obtiene información de sus proveedores   |      |
| US13           | Manejar las peticiones de los restaurantes de productos | Como usuario, quiero manejar las peticiones de productos de los restaurantes.                   | **Escenario 1:** El usuario quiere aceptar la petición de un restaurante| 4    |
|                |                                                    |                                                                                                  | **Escenario 2:** El usuario quiere rechazar la petición de un restaurante|      |
| US14           | Obtener un informe del dia de cambios en el almacén| Como usuario, quiero poder descargar un informe de los cambios del día en el inventario.        | **Escenario 1:** Usuario Descarga el informe del día                      | 3    |
|                |                                                    |                                                                                                  | **Escenario 2:** Usuario no puede Descarga el informe del día             |      |
| US15           | Agregar integrantes a mi grupo de inventario     | Como usuario, quiero agregar usuarios en mi grupo.                                                | **Escenario 1:** Usuario agrega correctamente a otro usuario             | 5    |
|                |                                                    |                                                                                                  | **Escenario 2:** Usuario agrega incorrectamente a otro usuario           |      |
| US16           | Asignar tareas a mi equipo                       | Como usuario, quiero asignar tareas del día a los integrantes de mi grupo.                       | **Escenario 1:** El usuario asigna una tarea a un integrante             | 5    |
|                |                                                    |                                                                                                  | **Escenario 2:** El usuario intenta asignar una tarea ya ocupada a un integrante|      |
| US17           | Eliminar integrantes de mi equipo                 | Como usuario, quiero eliminar personas de mi grupo.                                               | **Escenario 1:** El usuario elimina correctamente a un integrante        | 5    |
|                |                                                    |                                                                                                  | **Escenario 2:** El usuario elimina incorrectamente a un integrante      |      |
| US18           | Designar roles al equipo                          | Como usuario, quiero asignar roles a los integrantes de mi equipo.                                 | **Escenario 1:** El usuario asigna roles a su grupo                      | 5    |
| US19           | Notificar al usuario por productos vencer        | Como usuario, quiero recibir notificaciones de los productos a vencer.                             | **Escenario 1:** Usuario visualiza las notificaciones de productos a vencer| 3    |
| US20           | Notificar al usuario de cambios                   | Como usuario, quiero recibir notificaciones de cambios realizados en el inventario.                | **Escenario 1:** Usuario visualiza los cambios más importantes del inventario| 3    |
| US21           | Mostrar un resumen del inventario en el inicio   | Como usuario, quiero tener un resumen del inventario en el inicio.                                 | **Escenario 1:** El usuario visualiza el resumen del inventario en el inicio| 3    |
| US22           | Implementar un landing Page Responsive            | Como visitante, quiero interactuar en una landing page responsive, para que se adapte a la resolución de mi dispositivo. | **Escenario 1:** Usuario usa su pantalla 1920*1080                       | 6    |
|                |                                                    |                                                                                                  | **Escenario 2:** Usuario usa su pantalla 860*720                          |      |
| US23          | Implementar un cambio de idioma en el Landing Page| Como visitante, quiero poder cambiar de idioma para poder comprender el mensaje del landing page para poder compartir la idea del startup con el mundo.| **Escenario 1:** El usuario quiere cambiar de idioma correctamente       | 6    |
|                |                                                    |                                                                                                  | **Escenario 2:** El usuario quiere cambiar de idioma incorrectamente      |      |
| US24           | Sección sobre el servicio de FoodOs en el landing | Como visitante, quiero que el landing page me muestre una sección que da a conocer el producto.  | **Escenario 1:** Usuario quiere saber la finalidad del producto          | 6    |
| US25           | Sección sobre las membresías de FoodOs            | Como visitante, quiero que el landing page me muestre una sección.                                 | **Escenario 1:** Usuario quiere ver las membresías disponibles            | 6    |
| US26           | Sección que dirija a la app web de FoodOs        | Como visitante, quiero que el landing page me muestre una sección que me dirija a la aplicación web para empezar su uso. | **Escenario 1:** Usuario quiere ir al aplicación web                      | 6    |
| US27           | Sección sobre nosotros de TeamSync                | Como visitante, quiero que el landing page me muestre una sección sobre los desarrolladores del producto para mantenerme informado.| **Escenario 1:** Usuario quiere saber más del equipo                      | 6    |
| US28           | Sección de contacto de TeamSync                   | Como visitante, quiero que el landing page me muestre una sección que me ponga en contacto con la startup para mantenerme informado.| **Escenario 1:** Usuario llena el formulario para contactar con el startup| 6    |
| US29           | Subir fotos de perfil                             | Como usuario, quiero subir una imagen a mi perfil para poder personalizarla para mantenerme informado| **Escenario 1:** Carga de foto correcta                                    | 2    |
|                |                                                    |                                                                                                  | **Escenario 2:** Carga de la foto incorrecta                                |      |


## 3.3. Impact Mapping

![Usuario](/Assets/Img/Chapter%20III/IMPACTMAP.jpeg)
## 3.4. Product Backlog

| Orden | User Story ID | Título | Descripción | Story Points |
|-------|---------------|--------|-------------|--------------|
| 1     | US01          | Registro de cuenta | Como usuario, quiero crear una cuenta para ingresar a la aplicación. | 4 |
| 2     | US02          | Inicio de sesión   | Como usuario, quiero iniciar sesión con mi cuenta creada. | 4 |
| 3     | US03          | Cierre de sesión   | Como usuario, quiero poder cerrar mi sesión en la aplicación. | 4 |
| 4     | US04          | Actualizar información de cuenta | Como usuario, quiero mantener mi información de mi perfil actualizada. | 8 |
| 5     | US05          | Visualizar información de la cuenta | Como usuario, quiero poder visualizar la información de mi cuenta para verificarla. | 8 |
| 6     | US06          | Eliminar permanentemente la cuenta | Como usuario, quiero eliminar mi cuenta al no querer usar más la app. | 5 |
| 7     | US07          | Agregar un producto al inventario | Como usuario, quiero agregar un producto a mi inventario. | 5 |
| 8     | US08          | Eliminar un producto al inventario | Como usuario, quiero eliminar un producto de mi inventario. | 5 |
| 9     | US09          | Actualizar un producto al inventario | Como usuario, quiero actualizar los datos de un producto. | 5 |
| 10    | US10          | Ver todos los productos del inventario | Como usuario, quiero ver todos los productos del almacén. | 7 |
| 11    | US11          | Poder ver los productos prontos a vencer | Como usuario, quiero poder ver los productos que estén a punto de vencer para poder aprovecharlos en la producción. | 8 |
| 12    | US26          | Sección que dirija a la app web de FoodOs | Como visitante, quiero que el landing page me muestre una sección que me dirija a la aplicación web para empezar su uso. | 8 |
| 13    | US27          | Sección sobre nosotros de TeamSync | Como visitante, quiero que el landing page me muestre una sección sobre los desarrolladores del producto para mantenerme informado. | 8 |
| 14    | US28          | Sección de contacto de TeamSync | Como visitante, quiero que el landing page me muestre una sección que me ponga en contacto con la startup para mantenerme informado. | 8 |
| 15    | US25          | Sección sobre las membresías de FoodOs | Como visitante, quiero que el landing page me muestre una sección. | 8 |

