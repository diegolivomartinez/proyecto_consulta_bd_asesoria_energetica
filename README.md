# proyecto_consulta_bd_asesoria_energetica
Proyecto_consulta_bd_asesoria_energetica
# Consulta BD Asesoría Energética

Este proyecto es una aplicación web para consultar contratos energéticos. Permite a los usuarios buscar contratos por diferentes criterios y visualizar los resultados en una tabla y un gráfico.

## Descripción

La aplicación consiste en una página web donde los usuarios pueden realizar consultas sobre contratos energéticos almacenados en una base de datos. Los usuarios pueden seleccionar el criterio de búsqueda (CIF, Nombre, Comercializadora o Estado) y escribir la consulta en un campo de texto. Al hacer clic en el botón "Buscar", se muestran los resultados en una tabla y se genera un gráfico de barras que muestra el número de contratos por comercializadora.

## Recursos y Plataformas Utilizadas

- **Bootstrap**: Se utilizó Bootstrap (v4.5.2) para el diseño y la maquetación de la página web, lo que proporciona un aspecto moderno y responsivo.

- **Chart.js**: Se empleó Chart.js para generar el gráfico de barras que muestra la distribución de contratos por comercializadora. Este gráfico es dinámico y se actualiza en tiempo real según los resultados de la búsqueda.

- **JavaScript (script.js)**: El archivo `script.js` contiene el código JavaScript que maneja la interacción del usuario, como la búsqueda de contratos y la actualización de la tabla y el gráfico.

- **JSON (datos.json)**: Los datos de los contratos se almacenan en un archivo JSON llamado `datos.json`. Este archivo se carga dinámicamente utilizando la función `fetch()` en JavaScript.

- **CSS (styles.css)**: Se creó un archivo CSS llamado `styles.css` para personalizar el estilo de la página web. Se utilizan tonos de verde para darle un aspecto profesional y coherente.

## Instrucciones de Uso

1. Clona o descarga este repositorio en tu máquina local.
2. Abre el archivo `consulta.html` en tu navegador web.
3. Selecciona un criterio de búsqueda en el primer menú desplegable.
4. Escribe tu consulta en el campo de texto.
5. Haz clic en el botón "Buscar" para ver los resultados en la tabla y el gráfico.

## Autor

Este proyecto fue creado por [Tu Nombre].

Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto conmigo.

¡Gracias por tu interés en este proyecto!
