﻿
<h2 align="center">Proyecto Web con React: MascoTarea</h2>

------------

<p align="center">
Página desarrollada con el uso de distintas tecnologías, teniendo como base fundamental a React.
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/LAGAxyz/LAGAxyz/master/Foto%20(perfil).jpg" width="100">
</p>

<h5 align="center">Creado y Editado por</h5>
<p align="center">Luis Alberto Gutierrez Anicama (LAGA)</p>

<h5 align="center">Tecnologías usadas</h3>
<p align="center">
    <a> <img src="./skills/git.svg" width="40" height="40"/></a>
    <a> <img src="./skills/github.svg" width="40" height="40"/></a>
    <a> <img src="./skills/html5.svg" width="40" height="40"/></a>
    <a> <img src="./skills/css3.svg" width="40" height="40"/></a>
    <a> <img src="./skills/javascript.svg" width="40" height="40"/></a>
    <a> <img src="./skills/bootstrap.svg" width="40" height="40"/></a>
    <a> <img src="./skills/react.svg" width="40" height="40"/></a>
</p>

------------

## Documentación del proyecto:

1. Clona este repositorio con `git clone [URL]`

    *También puedes descargarlo directamente en formato .zip*

	> **Estructura del repositorio**
	* .git (hidden folder)
	* static (folder)
		+ css (folder)
			+ no delete files
		+ js (folder)
			+ no delete files
	* .gitignore
	* asset-manifest.json
	* Captura.PNG
	* favicon.ico
	* index.html
	* logo192.png
	* logo512.png
	* manifest.json
	* README.md
	* robots.txt

2. Ejecuta el archivo index.html

    *Deberías ver algo similar a lo siguiente*

    ![Captura](https://raw.githubusercontent.com/LAGAxyz/MascoTarea/master/Captura.PNG)
    
    > NOTA: Este proyecto necesita una API Key que puede no estar disponible en el momento en que lo ejecutes (para más información, continúa leyendo)

------------

### Sobre la API Key

Si el proyecto no funciona correctamente es posible que se deba a la desactualización de la API Key adjunta al proyecto actual, para solucionar este inconveniente deberá crear su propia API con los datos proporcionados abajo y usar su propia API Key.

**Recursos y atributos de la API**

La API debe tener los siguientes recursos y campos (es importante asignar los mismos tipos de datos indicados)

Recurso: Mascota | ----------
------------- | -------------
**Campo** | **Tipo**
mascota_id  | Object ID
mascota_nombre  | String
mascota_raza | Number
mascota_tipo | Number
mascota_edad | Number
mascota_colores | String
mascota_activo | Boolean

Recurso: Raza | ----------
------------- | -------------
**Campo** | **Tipo**
raza_id  | Object ID
raza_nombre  | String

Recurso: Tipo | ----------
------------- | -------------
**Campo** | **Tipo**
tipo_id  | Object ID
tipo_nombre  | String

**La API Key**

Una vez creada la API con los recursos, campos y tipos de datos mencionados arriba; debe solicitar su API Key, la cual debe tener la siguiente estructura:

`https://SECRET.API.Key/[endpoint]`

> NOTA: Reemplazar [endpoint] por el recurso a utilizar

**Finalmente:** Reemplazar la API Key del proyecto que se encuentra en el archivo `main.3161ce7e.chunk.js` por su propia API Key.
