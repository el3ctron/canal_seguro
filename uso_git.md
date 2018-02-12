Una vez instalado git:

1. Abre una consola y ubícate en el directorio en el que quieras trabajar
        cd /ruta/al/directorio/donde_quiero/trabajar
2. Crea una copia local del repositorio del proyecto ejecutando
        git clone /path/to/repository
    Si utilizas un servidor remoto, ejecuta
        git clone username@host:/path/to/repository
3. Inicia tu trabajo y guarda los cambios
   Puedes registrar cambios (añadirlos al Index) usando
       git add <filename>
       git add .
   Este es el primer paso en el flujo de trabajo básico. Para hacer commit a estos cambios usa
       git commit -m "Commit message"
   Ahora el archivo esta incluído en el HEAD, pero aún no en tu repositorio remoto.
4. envío de cambios
   Tus cambios están ahora en el HEAD de tu copia local. Para enviar estos cambios a tu repositorio remoto ejecuta
       git push origin master
   Reemplaza master por la rama a la que quieres enviar tus cambios.

# Recomendaciones importantes
    * Cada vez que vayas a trabajar en el proyecto asegurate de descargar las últimas actualizaciones, para actualizar tu repositorio local al commit más nuevo, para bajar y fusionar los cambios remotos, ejecuta en tu directorio de trabajo:
        git pull

    * Interfaz gráfica por defecto
        gitk

    * Colores especiales para la consola
        git config color.ui true

    * Mostrar sólo una línea por cada commit en la traza
        git config format.pretty oneline

    * Agregar archivos de forma interactiva
        git add -i
