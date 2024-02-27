# Coderhouse - Pre-entrega 2

Este proyecto es parte de una serie de entregas para el curso de Coder House. La presente versión corresponde a la pre-entrega número 2, donde se ha avanzado en la consulta de la API del BCRA (Banco Central de la República Argentina), recopilando distintos datos de interés.

## Descripción del Proyecto

El script principal de este repositorio, `bcra-consolidate.py`, está diseñado para interactuar con la API del BCRA y obtener información valiosa que luego es procesada y almacenada. Este proceso forma parte de un ejercicio educativo para aplicar conocimientos de programación en Python, consulta de APIs, manejo de bases de datos, y versionamiento de código con Git y GitHub.

## Configuración

Para que el script funcione correctamente, es necesario realizar una configuración inicial que incluye la creación de un archivo `config.ini`. Este archivo debe contener las credenciales y datos de acceso para la API del BCRA y para la conexión con una base de datos Redshift.

### Estructura del archivo `config.ini`

El archivo `config.ini` debe tener la siguiente estructura:

[api_bcra]
token = TU_TOKEN_AQUI

[redshift]
host = TU_HOST_AQUI
dbname = TU_DBNAME_AQUI
user = TU_USER_AQUI
password = TU_PASSWORD_AQUI
port = TU_PORT_AQUI

Un ejemplo de este archivo ha sido enviado junto con el link de GitHub en un archivo `.txt` adjunto para referencia.

### Instalación de Dependencias

Antes de ejecutar el script, asegúrate de instalar las librerías necesarias listadas en el archivo `requirements.txt` utilizando el siguiente comando:

pip install -r requirements.txt

### Ejecución del Script Principal

Una vez configurado el entorno, puedes ejecutar el script principal con el comando:

python bcra-consolidate.py

## Comentarios y Buenas Prácticas

Actualmente, mi rol profesional está enfocado en infraestructura, por lo que mi interacción diaria con herramientas como Python, SQL, y GitHub no es constante. Sin embargo, he realizado un esfuerzo por documentar adecuadamente el código y proveer instrucciones claras para su ejecución en este archivo README.

Cualquier feedback relacionado con las buenas prácticas en compartir y documentar proyectos de software será enormemente apreciado. ¡Espero que el código sea comprensible y que este README facilite su uso y comprensión!

## Contacto

Si tienes preguntas o comentarios sobre este proyecto, no dudes en abrir un issue en el repositorio o contactarme directamente (opcional: agregar información de contacto).
