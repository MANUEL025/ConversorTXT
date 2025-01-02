# Chat Processor

Este es un procesador de chats en formato `.txt` que permite extraer información de los mensajes, procesarlos y generar un archivo Excel (.xlsx) descargable. El proyecto está diseñado para facilitar el análisis de chats y generar reportes estructurados con fechas, horas, mensajes y novedades.

## Descripción

El procesador lee un archivo de texto con un formato de chat específico, extrae los mensajes y genera un archivo Excel con la siguiente estructura:

- **Fecha**: La fecha en que se envió el mensaje.
- **Hora**: La hora exacta del mensaje.
- **Timestamp**: Una combinación de fecha y hora.
- **Mensaje**: El contenido del mensaje.
- **Novedad**: Un indicador de si el mensaje contiene una novedad (por ejemplo, "SIEDCO PLUS").

El sistema permite ignorar mensajes con imágenes omitidas o números de teléfono y marcar ciertos mensajes con novedades como "SIEDCO PLUS".

## Características

- Carga archivos `.txt` con formato de chat.
- Procesa las líneas del archivo y extrae la fecha, hora, remitente y mensaje.
- Marca los mensajes que contienen "SIEDCO PLUS" como novedades.
- Ignora mensajes con "imagen omitida" o números de teléfono.
- Genera un archivo Excel con los datos procesados.

## Tecnologías utilizadas

- **HTML**: Estructura de la página web.
- **JavaScript**: Lógica para procesar el archivo de texto y generar el archivo Excel.
- **XLSX.js**: Librería para generar archivos Excel desde JavaScript.
- **CSS**: Estilos básicos para la interfaz.

## Instalación

Este proyecto no requiere instalación. Solo necesitas un navegador web moderno que soporte JavaScript.


