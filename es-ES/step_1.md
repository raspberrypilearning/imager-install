## Instala Raspbian en tu tarjeta SD con el Raspberry Pi Imager

Muchos proveedores venden tarjetas SD con un instalador simple de Raspbian llamado NOOBS ya preinstalado, pero puedes instalar Raspbian fácilmente usando un ordenador que tenga un puerto de tarjeta SD o un lector de tarjetas SD.

Usar el Raspberry Pi Imager es la forma más fácil de instalar Raspbian en tu tarjeta SD.

**Nota:** Los usuarios más avanzados que deseen instalar un sistema operativo en particular deben usar esta guía para [instalar imágenes del sistema operativo](https://www.raspberrypi.org/documentation/installation/installing-images/README.md).

### Descarga y ejecuta el Raspberry Pi Imager

+ Visita la [página de descargas de Raspberry Pi](https://www.raspberrypi.org/downloads).
+ Haz clic en el enlace de Raspberry Pi Imager que coincida con tu sistema operativo.

![Página de descargas](images/newInstaller_downloadsPage.png)

+ Cuando finalice la descarga, haz clic en ella para iniciar el instalador.

![Iniciar instalador](images/newInstaller_launchInstaller.png)

### Usando el Raspberry Pi Imager

Todos los datos almacenados en la tarjeta SD se sobrescribirán durante el formateo y se perderán permanentemente, así que asegúrate de hacer una copia de seguridad de la tarjeta o de los archivos que desees conservar antes de ejecutar el instalador.

Cuando inicias el instalador, tu sistema operativo puede intentar bloquear su ejecución. Por ejemplo, Windows puede dar el siguiente mensaje:

![Advertencia de Windows](images/newInstaller_windowsWarning.png)

+ Si obtienes esto, haz clic en `Más información` y luego `Ejecutar de todos modos`.

+ Inserta tu tarjeta SD en la ranura para tarjetas SD del ordenador o del portátil.

+ En el Raspberry Pi Imager, selecciona el sistema operativo que deseas instalar. La primera opción, Raspbian, es el sistema operativo recomendado.

![Raspberry Pi Imager en ventanas](images/newInstaller_selectOS.png)

+ Selecciona la tarjeta SD en la que deseas instalarlo. Las diferentes plataformas mostrarán las unidades de diferentes maneras. El sistema operativo Mac, por ejemplo, te mostrará todas las unidades, incluido el sistema operativo principal.

**Nota:** Asegúrate de seleccionar la unidad correcta. La capacidad de memoria de las unidades puede ser una indicación útil para saber qué unidad estás seleccionando.

![Raspberry Pi Imager en ventanas](images/newInstaller_select-SDCard.png)

Una vez que hayas seleccionado tanto el sistema operativo como la tarjeta SD, aparecerá un nuevo botón `WRITE` (Nota: escribir).

![Raspberry Pi Imager en ventanas](images/newInstaller_osAndCardSelected.png)

+ Luego simplemente haz clic en el botón `ESCRIBIR`.

+ Espera a que Raspberry Pi Imager termine de escribir.

+ Una vez que recibas el siguiente mensaje, puedes expulsar tu tarjeta SD.

![Mensaje de Escritura con éxito](images/newInstaller_writeSuccessful.png)
