# World Cup 2022 Python Bot

## Un bot en discord capaz de darte información de interés sobre partidos, encuentros y puntajes de tus equipos favoritos dentro de este nuevo mundial de fútbol Qatar 2022

El bot correrá en cualquier computadora siempre y cuando se sigan los siguientes pasos para una correcta instalación ♥
---
### Características:

#### Comandos del bot:

`!hola` este comando te dará una rápida bienvenida al bot, así como te dará el primer comando que debes colocar para así obtner mas información de lo que puede hacer.

![imagen1final](https://drive.google.com/file/d/1EsfpHQDQvb3lFzTbTykrghVihTvxVM9Q/view?usp=share_link)

`!ayuda` Un comando básico para así obtener la información necesaria sobre todos los comandos y la forma enque debes registrarte e iniciar sesión.

![imagen2final](https://drive.google.com/file/d/1gQUnHu6Lr6wLdL6XLLLfMVA6sL6IiB9s/view?usp=share_link)

`!registro` Funciona para poder ingresar en la base de datos del bot, sin este registro no podras iniciar ni realizar ninguna acción (la forma en la que debes registrate está en el comando de ayuda).

![imagen3final](https://drive.google.com/file/d/1yVgWBRjvzdM1r0CjSLy2-9S0617IZwjb/view?usp=sharing)

`!usuario` Te ayuda a conocer el nombre de usuario que colocaste como registro.

![imagen4final](https://drive.google.com/file/d/1Lr4OQ4rLCeW0LRZmR88BpKBfq14J1xYa/view?usp=share_link)

`!iniciar` Comando simple para que el bot de inicio a todas sus funciones, si el registro fue satisfactorio deberás obtener un mensaje que diga: ***_Iniciaste sesion_***.

![imagen5final](https://drive.google.com/file/d/1bcB3qw75hPDoDmb1LYpvcHCOed89EkPi/view?usp=share_link)

`!equipo` Coloca este comando seguido de el equipo del cual quieras obtener información; es **importante que el nombre del equipo que vayas a colocar este en inglés**.

![imagen6final](https://drive.google.com/file/d/1BwKY9ilwW7rQr-IQx3Zr2m1hvP1PCs_t/view?usp=share_link)

`!partidos` Al igual que el comando anterior ingresa este seguido del **nombre del equipo en inglés** para aí obtener información de los proximos encuentrso de tus equipos favoritos.

![imagen7final](https://drive.google.com/file/d/19wZg-TtR4laQtXNaJJ2zRugGWdI9hHa1/view?usp=share_link)

`!grupo` Busca tambien por grupos y así obtendrás los puntajes de un grupo determinado dentro de este mundial.

![imagen8final](https://drive.google.com/file/d/1uC_F6pxlKYAqdd414bCwDXpgNeZVGK-m/view?usp=share_link)

***

### Herramientas necearias para instalar el bot:

#### Windows 10:

*	Instala Python en su versión 3.10.8 (***es necesario que sea la versión antes mencionada para que el bot pueda funcionar, versiones posteriores no son soportadas***); ( https://www.python.org/downloads/)
*	Como editor de código usaremos Visual Studio Code; existen muchas alternativas, sin embargo, el código está hecho en este editor.
*	Lugo de haber instalado Visual Studio Code, es necesario instalar la extensión de SQLITE, la cual nos ayudará a ver y crear la base de datos.
*	Es necesario instalar todas las dependencias que se encuentran al inicio del código, tales como `json`, `PIL` , entre otros.
*	Descarga Git para Windows, este te permitirá clonar el código más adelante; descárgalo a través de su web oficial: ( https://gitforwindows.org/).

#### Descargar el código:

1.	Crea una carpeta y ábrela con Visual Studio Code.
2.	En el terminal de VSCODE copia el siguiente comando:

`git clone https://github.com/Storgaro/python-bot`

Posteriormente da enter en _SI_ y espera a que la descarga de todos los archivos termine. ***Es necesario que deje su terminal abierto y siga con los siguientes pasos***

#### Configuración del Bot 

1.	En tu buscador de preferencia dirígete a la página de [Discord developer]( https://discord.com/developers/applications.).
2.	Clickea en el botón de **New Application**
3.	Posteriormente coloca el nombre que gustes a tu **Servidor de Discord**
4.	En el menu de la izquierda selecciona la pestaña de Bot.
5.	Daremos click donde dice **Add Bot**
6.	En este apartado daremos nombre al Bot y daremos click en el botón de **Reset Token**.
7.	Copiaremos el nuevo **Token** dado por el Bot y lo reservaremos para más adelante.

#### Creando el URL para añadir el bot al servidor:

1.	Nos dirigimos al menú del lado izquierdo y presionaremos la opción **OAuth2**; Copiaremos el **Cient ID** y lo reservaremos para más adelante.
2.	Daremos click al **URL GENERTOR** y seleccionaremos las opciones de **bot** y ** applications.commands**
3.	Posteriormente marcaremos las casillas de los permisos, en estos seleccionaremos los mostrados a continuación.
4.	Copiaremos el **URL** que nos da al final y lo pegaremos en el navegador. Este traerá un menú de Discord y nos preguntará a que servidor queremos añadir el bot. Aquí seleccionaremos el servidor que creamos hace un momento y daremos **Confirmar**.

Por último, ya tenemos el bot dentro de nuestro servidor y ahora procederemos a activar sus funciones.

#### Configurando el bot:

Primero, deberá completar su archivo **env**. (***El bot viene con un archivo example.env, el cual deberá renombrar a env***). Aquí deberá agregar su **token del bot y la ID de cliente para el bot**.
_Consulte el archivo ejemplo.env para obtener más información._

#### Instalar las dependenciaas necesarias:

En su terminal escruba el siguiente códigoÑ

`pip install`

Seguido del nombre de la dependencia que le haga falta (**Las dependencias necesarias se encuentran en los IMPORT al inicio del código**).

### Poner a funcionar el Bot:

En su terminal escriba el siguiente comando:

`py (_seguido del nombre de su archivo .py_)`

Posteriormente presione **Enter** y disfrute de todas las opciones y comandos que este bot le ofrece.
