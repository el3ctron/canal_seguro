![](https://snipcart.com/media/10182/git-based-content-workflow-github.jpg)

1. Manual de instalación de git

    **Instalando en Windows**

        Instalar Git en Windows es muy fácil. El proyecto msysGit tiene uno de los procesos de instalación más sencillos. Simplemente descarga el archivo exe del instalador desde la página de GitHub, y ejecútalo:

        http://msysgit.github.com/

        Una vez instalado, tendrás tanto la versión de línea de comandos (incluido un cliente SSH que nos será útil más adelante) como la interfaz gráfica de usuario estándar.

    **Instalando en Mac**

        Hay tres maneras fáciles de instalar Git en un Mac. La más sencilla es usar el instalador gráfico de Git, que puedes descargar desde la página de SourceForge

        http://sourceforge.net/projects/git-osx-installer/

    **Instalando en Linux**

        Si quieres instalar Git en Linux a través de un instalador binario, en general puedes hacerlo a través de la herramienta básica de gestión de paquetes que trae tu distribución. Si estás en Fedora, puedes usar yum:

        $ yum install git-core

        O si estás en una distribución basada en Debian como Ubuntu, prueba con apt-get:

        $ apt-get install git

2. Manual para descargar el repositorio

    2.1. ubícate en la carpeta donde quieres que el proyecto quede en tu computador
    2.2. copia la ubicación de esa carpeta
    2.3. abre una consola luego pega la ruta de esa carpeta anteponiendo el comando "cd" así:
        cd [ruta de la carpeta en tu computadora donde quieres que quede el proyecto]
    2.4. verifica que estás en la carpeta que quieres
    2.5. escribe en la consola el comando
        git clone [url del proyecto]
    2.6. listo!
