# World Cup 2022 Python Bot

## Un bot en discord capaz de darte información de interés sobre partidos, encuentros y puntajes de tus equipos favoritos dentro de este nuevo mundial de fútbol Qatar 2022

El bot correrá en cualquier computadora siempre y cuando se sigan los siguientes pasos para una correcta instalación ♥
---
### Características:

#### Comandos del bot:

`!hola` este comando te dará una rápida bienvenida al bot, así como te dará el primer comando que debes colocar para así obtner mas información de lo que puede hacer.

![imagen1def](https://raw.githubusercontent.com/Storgaro/imagenes/main/images.md/imagen-1-final.png?token=GHSAT0AAAAAAB4FVQQLULOGVVJM2IHL42K4Y4TOQPQ)

`!ayuda` Un comando básico para así obtener la información necesaria sobre todos los comandos y la forma enque debes registrarte e iniciar sesión.

![imagen2final](https://raw.githubusercontent.com/Storgaro/imagenes/main/images.md/image2def.png?token=GHSAT0AAAAAAB4FVQQKVAVJ24D7DHBHR4RWY4TOQZQ)

`!registro` Funciona para poder ingresar en la base de datos del bot, sin este registro no podras iniciar ni realizar ninguna acción (la forma en la que debes registrate está en el comando de ayuda).

![imagen3final](https://raw.githubusercontent.com/Storgaro/imagenes/main/images.md/imagen3def.png?token=GHSAT0AAAAAAB4FVQQL4Q4ASW3UIABPMSQUY4TORDA)

`!usuario` Te ayuda a conocer el nombre de usuario que colocaste como registro.

![imagen4final](https://raw.githubusercontent.com/Storgaro/imagenes/main/images.md/imagen4def.png?token=GHSAT0AAAAAAB4FVQQKMLLVJLKQAOO7YLL2Y4TOTHQ)

`!iniciar` Comando simple para que el bot de inicio a todas sus funciones, si el registro fue satisfactorio deberás obtener un mensaje que diga: ***_Iniciaste sesion_***.

![imagen5final](https://raw.githubusercontent.com/Storgaro/imagenes/main/images.md/imagen5def.png?token=GHSAT0AAAAAAB4FVQQLGNCJUFUBTUJQVNHSY4TOS7Q)

`!equipo` Coloca este comando seguido de el equipo del cual quieras obtener información; es **importante que el nombre del equipo que vayas a colocar este en inglés**.

![imagen6final](https://github.com/Storgaro/imagenes/blob/main/images.md/imagen6def.png)

`!partidos` Al igual que el comando anterior ingresa este seguido del **nombre del equipo en inglés** para aí obtener información de los proximos encuentrso de tus equipos favoritos.

![imagen7final](https://raw.githubusercontent.com/Storgaro/imagenes/main/images.md/imagen7def.png?token=GHSAT0AAAAAAB4FVQQKG2Q7HWDLW3HRZHD4Y4TOSMA)

`!grupo` Busca tambien por grupos y así obtendrás los puntajes de un grupo determinado dentro de este mundial.

![imagen8final](https://raw.githubusercontent.com/Storgaro/imagenes/main/images.md/imagen8def_1.png?token=GHSAT0AAAAAAB4FVQQKQIJMI6IXQISOA74MY4TOSTQ)

***

### Herramientas necearias para instalar el bot:

#### Windows:

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

![imagen9final](https://user-images.githubusercontent.com/8563780/162317136-4373626f-9f7a-4d7f-880c-60e470c64d69.png)

3.	Posteriormente coloca el nombre que gustes a tu **Servidor de Discord**
4.	En el menu de la izquierda selecciona la pestaña de Bot.

![imagen10final](https://user-images.githubusercontent.com/8563780/162320423-275012d1-dc06-4c10-b954-b3cd86322c2c.png)

5.	Daremos click donde dice **Add Bot**

![imagen11final](https://user-images.githubusercontent.com/8563780/162321199-e5b00e88-4720-45c4-86c1-0da4bf47ebf1.png)

6.	En este apartado daremos nombre al Bot y daremos click en el botón de **Reset Token**.

![imagen12final](https://user-images.githubusercontent.com/8563780/162322546-7119e7b5-fe30-42e2-9369-4f695f87d3d7.png)

7.	Copiaremos el nuevo **Token** dado por el Bot y lo reservaremos para más adelante.

#### Creando el URL para añadir el bot al servidor:

1.	Nos dirigimos al menú del lado izquierdo y presionaremos la opción **OAuth2**; Copiaremos el **Cient ID** y lo reservaremos para más adelante.

![imagen13final](https://user-images.githubusercontent.com/8563780/162323888-77958a62-0aab-403a-9f56-1688b30ccdef.png)

![imagen14final](https://user-images.githubusercontent.com/8563780/162325239-fde9fef0-9e1f-4a39-b92e-a297c73991a7.png)


2.	Daremos click al **URL GENERTOR** y seleccionaremos las opciones de **bot** y **applications.commands**

![imagen15final](https://user-images.githubusercontent.com/8563780/162325504-68045770-e28e-404c-a441-b9192f0a55a5.png)

3.	Posteriormente marcaremos las casillas de los permisos, en estos seleccionaremos los mostrados a continuación.

![imagen16final](https://raw.githubusercontent.com/Storgaro/imagenes/main/images.md/imagen16final.png?token=GHSAT0AAAAAAB4FVQQLJ2KRZM63HJB5WHTMY4TOEKQ)

4.	Copiaremos el **URL** que nos da al final y lo pegaremos en el navegador. Este traerá un menú de Discord y nos preguntará a que servidor queremos añadir el bot. Aquí seleccionaremos el servidor que creamos hace un momento y daremos **Confirmar**.


![imagen17final](https://raw.githubusercontent.com/Storgaro/imagenes/main/images.md/imagen17final.png?token=GHSAT0AAAAAAB4FVQQKEFA5Y4BF52LJU7GGY4TOEVA)

Por último, ya tenemos el bot dentro de nuestro servidor y ahora procederemos a activar sus funciones.

#### Configurando el bot:

Primero, deberá completar su archivo **env**. (***El bot viene con un archivo example.env, el cual deberá renombrar a env***). Aquí deberá agregar su **token del bot y la ID de cliente para el bot**.
_Consulte el archivo ejemplo.env para obtener más información._

#### Instalar las dependenciaas necesarias:

En su terminal escruba el siguiente códigoÑ

`pip install (Seguido del nombre de la dependencia que le haga falta)`

(**Las dependencias necesarias se encuentran en los IMPORT al inicio del código**).

### Poner a funcionar el Bot:

En su terminal escriba el siguiente comando:

`py (seguido del nombre de su archivo .py)`

Posteriormente presione **Enter** y disfrute de todas las opciones y comandos que este bot le ofrece.
