## Instala Raspberry Pi OS en tu tarjeta SD con Raspberry Pi Imager

Muchos proveedores venden tarjetas SD con un instalador preinstalado de Raspbian llamado NOOBS, pero puedes instalar Raspberry Pi OS fácilmente usando un ordenador que tenga un puerto de tarjeta SD o un lector de tarjetas SD.

Usar Raspberry Pi Imager es la forma más fácil de instalar Raspberry Pi OS en tu tarjeta SD.

**Nota:** Los usuarios más avanzados que deseen instalar un sistema operativo en particular deberían usar esta guía para [instalar imágenes de sistema operativo](https://www.raspberrypi.org/documentation/installation/installing-images/README.md).

### Descarga y ejecuta Raspberry Pi Imager

+ Visita la [página de descargas de Raspberry Pi](https://www.raspberrypi.org/downloads).
+ Haz clic en el enlace de Raspberry Pi Imager que coincida con tu sistema operativo.

![Página de descargas](images/newInstaller_downloadsPage.png)

+ Cuando finalice la descarga, haz clic en él para iniciar el instalador.

![Iniciar instalador](images/newInstaller_launchInstaller.png)

### Usando Raspberry Pi Imager

Todos los datos almacenados en la tarjeta SD se sobrescribirán durante el formateo y se perderán permanentemente, así que asegúrate de hacer una copia de seguridad de la tarjeta o de los archivos que desees conservar antes de ejecutar el instalador.

Cuando inicies el instalador, tu sistema operativo quizás intente evitar que lo ejecutes. Por ejemplo, Windows puede dar el siguiente mensaje:

![Advertencia de Windows](images/newInstaller_windowsWarning.png)

+ Si obtienes esto, haz clic en `Más información` y luego `Ejecutar de todos modos`.

+ Inserta tu tarjeta SD en la ranura para tarjetas SD de la computadora o portátil.

+ En Raspberry Pi Imager, selecciona el SO que deseas instalar. La primera opción, Raspberry Pi OS, es el sistema operativo recomendado.

![Raspberry Pi Imager en ventanas](images/newInstaller_selectOS.png)

+ Selecciona la tarjeta SD en la que deseas instalarlo. Diferentes plataformas mostrarán las unidades de diferentes maneras. macOS, por ejemplo, te mostrará todas las unidades, incluído el sistema operativo principal.

**Nota:** Asegúrate de seleccionar la unidad correcta. La capacidad de memoria de las unidades puede ser un indicativo útil de qué unidad estás seleccionando.

![Raspberry Pi Imager en ventanas](images/newInstaller_select-SDCard.png)

Una vez que hayas seleccionado tanto el sistema operativo como la tarjeta SD, aparecerá un nuevo botón `WRITE`.

![Raspberry Pi Imager en ventanas](images/newInstaller_osAndCardSelected.png)

+ Luego, haz clic en el botón `WRITE`.

+ Espera a que Raspberry Pi Imager termine de escribir.

+ Una vez que recibas el siguiente mensaje, puedes retirar tu tarjeta SD.

![Mensaje de Escritura exitosa](images/newInstaller_writeSuccessful.png)
