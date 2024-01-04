# Qa project 07 

Este proyecto de automatización utiliza Selenium WebDriver para interactuar con la página web de Urban Routes y realizar diversas acciones, como establecer rutas, ingresar información de pago, y verificar la funcionalidad de la interfaz.

El código proporcionado contiene la clase `UrbanRoutesPage` que representa la interacción con elementos específicos de la página web de Urban Routes. La clase utiliza Selenium WebDriver para interactuar con los elementos de la página, como campos de dirección, botones y secciones de información de pago.

## Información de Prueba

Se utilizaron los siguientes datos para realizar pruebas de automatización:

- **URL de Urban Routes**: [https://c1b1695b-dfc0-4814-ac1a-20316d24d418.serverhub.tripleten-services.com?lng=es]
- **Dirección de Origen**: 'East 2nd Street, 601'
- **Dirección de Destino**: '1300 1st St'
- **Número de Teléfono**: '+1 123 123 12 12'
- **Número de Tarjeta de Pago**: '1234 5678 9100'
- **Mensaje para el Conductor**: 'Ruta hacia el museo'
- **CVV de la Tarjeta de Pago**: '111'

## Estructura del Código

El código está estructurado de la siguiente manera:

- Definición de elementos de la página utilizando selectores XPath y IDs. La mayoría de elementos fueron localizados By. XPATH ya que el servidor cambia constantemente y algunos XPath estan codificados debido a que otros elementos tienen el mismo nombre o la estructura del xpath simplificado era más larga que la versión codificada.
- Métodos para establecer rutas, ingresar números de teléfono, información de tarjetas de pago, mensajes para el conductor, entre otros.
- Se incluyen métodos de prueba utilizando el framework de pruebas pytest para verificar la funcionalidad de la clase `UrbanRoutesPage`.

## Requisitos y Configuración

Este código requiere la instalación de Python y la biblioteca Selenium. Se utilizó el navegador Chrome con el controlador Chrome WebDriver.
Antes de empezar las pruebas se instalaron los paquetes: pip, pytest y se exportaron los siguientes datos:

import data
from selenium import webdriver
from selenium.webdriver.common.by import By
from selenium.webdriver.support.ui import WebDriverWait
from selenium.common.exceptions import NoSuchElementException
from selenium.webdriver.support import expected_conditions as EC
from selenium.common.exceptions import ElementNotInteractableException

La configuración fijada en "current file" corre ocho pruebas que fueron aprobadas.


¡Gracias por revisar este proyecto!
