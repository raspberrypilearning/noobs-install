### Descargando NOOBS

Usar NOOBS es la forma más fácil de instalar Raspbian en su tarjeta SD. Para obtener una copia de NOOBS:

+ Visita [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Página de descargas](images/downloads-page.png)

+ Debería ver un cuadro con un enlace a los archivos de NOOBS. Clic en el enlace.

![Haga clic en NOOBS](images/click-noobs.png)

+ La opción más simple es descargar el archivo zip de los archivos.

![Descargar zip](images/download-zip.png)

### Formateo de la tarjeta SD

Si la tarjeta SD en la que desea instalar Raspbian actualmente tiene una versión anterior de Raspbian, es recomendable que haga una copia de seguridad de los archivos de la tarjeta, ya que se sobrescribirán durante este proceso.

+ Visite el sitio web de la Asociación SD y descargue [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) para Windows o Mac.

+ Siga las instrucciones para instalar el software.

+ Inserte su tarjeta SD en el lector de tarjetas SD de la computadora o computadora portátil y anote la letra de la unidad asignada, por ejemplo `F: /`.

+ En SD Formatter, seleccione la letra de la unidad de su tarjeta SD y formatéela.

### Extrayendo NOOBS del archivo zip

A continuación, deberá extraer los archivos del archivo zip de NOOBS que descargó del sitio web de Raspberry Pi.

+ Vaya a su carpeta *Descargas* y encuentre el archivo comprimido que descargó.

+ Extraiga los archivos y mantenga abierta la ventana resultante del Explorador / Buscador.

### Copiando los archivos

+ Ahora abra otra ventana Explorer / Finder y navegue a la tarjeta SD. Lo mejor es colocar las dos ventanas una al lado de la otra.

+ Seleccione todos los archivos de la carpeta *NOOBS* y arrástrelos a la tarjeta SD.

![copia de ventanas](images/copy3.png)

![macos copia](images/macos_copy.png)

+ Expulsa la tarjeta SD.

### Arranque desde NOOBS

+ Una vez que los archivos han sido copiados, inserte la tarjeta micro SD en su Raspberry Pi, y conecte el Pi a una fuente de alimentación.

+ Se le ofrecerá una opción cuando el instalador se haya cargado. Debe marcar la casilla para **Raspbian**, y luego haga clic en **Install**.

![instalar](images/install.png)

+ Haga clic en **Sí** en el cuadro de diálogo de advertencia, y luego siéntese y relájese. Llevará un tiempo, pero Raspbian se instalará.

![instalando](images/installing.png)

+ Cuando se haya instalado Raspbian, haga clic en **OK** y su Raspberry Pi se reiniciará y Raspbian se iniciará.

![instalado](images/installed.png)