# Qa project 07 

Este proyecto de automatización utiliza Selenium WebDriver para interactuar con la página web de Urban Routes y realizar diversas acciones, como establecer rutas, ingresar información de pago, y verificar la funcionalidad de la interfaz.

El código proporcionado contiene la clase `UrbanRoutesPage` que representa la interacción con elementos específicos de la página web de Urban Routes. La clase utiliza Selenium WebDriver para interactuar con los elementos de la página, como campos de dirección, botones y secciones de información de pago.

## Información de Prueba

Se utilizaron los siguientes datos para realizar pruebas de automatización:

- **URL de Urban Routes**: [https://091e5582-d000-4242-9aa7-155979419674.serverhub.tripleten-services.com?lng=es](https://091e5582-d000-4242-9aa7-155979419674.serverhub.tripleten-services.com?lng=es)
- **Dirección de Origen**: 'East 2nd Street, 601'
- **Dirección de Destino**: '1300 1st St'
- **Número de Teléfono**: '+1 123 123 12 12'
- **Número de Tarjeta de Pago**: '1234 5678 9100'
- **Mensaje para el Conductor**: 'Ruta hacia el museo'
- **CVV de la Tarjeta de Pago**: '111'

## Estructura del Código

El código está estructurado de la siguiente manera:

- Definición de elementos de la página utilizando selectores XPath y IDs.
- Métodos para establecer rutas, ingresar números de teléfono, información de tarjetas de pago, mensajes para el conductor, entre otros.
- Se incluyen métodos de prueba utilizando el framework de pruebas pytest para verificar la funcionalidad de la clase `UrbanRoutesPage`.

## Requisitos y Configuración

Este código requiere la instalación de Python y la biblioteca Selenium. Se utilizó el navegador Chrome con el controlador Chrome WebDriver.

Luego de tener todo el entorno configurado, las ocho pruebas fueron aprobadas.


¡Gracias por revisar este proyecto!
