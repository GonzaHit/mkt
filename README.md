# mkt

Este script en Bash crea una estructura de directorios basada en la fecha y la hora actuales, y guarda una dirección IP proporcionada por el usuario en un archivo de texto.

Descripción
El script verifica si se ha ingresado una dirección IP como argumento. Si no se ingresa, muestra un mensaje de uso y termina. Si se ingresa una dirección IP, el script crea una estructura de directorios con un nombre basado en la fecha y hora actuales, y guarda la IP en un archivo ip.txt dentro del directorio creado.

Requisitos
Tener Bash instalado.

Uso
Clona el repositorio:

bash
git clone <URL_del_repositorio>
cd <nombre_del_repositorio>

Asigna permisos de ejecución al script:

bash
chmod +x mkt

Instalar en /usr/local/bin/

Ejecuta el script con una dirección IP como argumento:

bash

mkt <IP>

Estructura de Directorios

El script crea la siguiente estructura de directorios:

<nombre_del_proyecto>/

├── nmap/

├── content/

├── exploits/

└── scripts/

└── ip.txt (contiene la IP proporcionada)
