# Mi Primer Servidor HTTP
La práctica consiste en implementar varias etapas que incluyen desde un simple "Hola Mundo" hasta un servidor asíncrono que lee y envía archivos según su extensión.
## Empezando
Estas instrucciones te guiarán a través de la configuración y el uso del servidor HTTP en Node.js.
### Requisitos Previos
Node.js
### Instalación
1. Ve a la terminal
2. Actualiza el índice de paquetes: “sudo apt update”
3. Instala Node.js y npm: “sudo apt install nodejs npm”
4. Verifica la instalación: “node -v” y “npm -v”
## Ejecutando el Servidor
Para iniciar el servidor, ejecuta el comando: node app.js
El servidor escuchara en el puerto 4444.
## Etapas del Proyecto
### Hola mundo básico
Esta etapa consiste en configurar un script de Node.js que imprime "Hola Mundo" en la consola.
### Servidor HTTP Simple de Hola Mundo
Se crea un servidor HTTP básico utilizando el módulo http que responde con "Hola Mundo" a cualquier solicitud.
### Servidor Síncrono que Lee y Envía un Archivo
Se crea un servidor que lee y envía un archivo de forma síncrona. Cuando se recibe una solicitud, el servidor lee un archivo específico del sistema de archivos y envía su contenido en la respuesta.
### Servidor Asíncrono que Lee y Envía un Archivo
Esta etapa mejora la anterior leyendo y enviando archivos de forma asíncrona.
### Servidor Asíncrono que Lee y Envía un Archivo Según su Extensión
En la etapa final extiende el servidor asíncrono para servir archivos según sus extensiones. El servidor determina el tipo de contenido apropiado y responde en consecuencia.
## Estructura del proyecto
App.js
WWW (index.html, readme.txt y ventas.html)

## Autor
Angelica Torres Velderrain 359628
