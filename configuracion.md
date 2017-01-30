

# Configuración



## Preparación para la instalación de Enigmail

Cuando Mozilla se ejecuta por primera vez, verás una pequeña ventana de confirmación preguntando sobre algunos ajustes predeterminados. Se recomienda hacer clic en el botón "Establecer como predeterminado".

![](https://ssd.eff.org/files/2016/08/12/020.png)

Cuando Mozilla Thunderbird inicia por primera vez, te preguntará si deseas abrir una nueva dirección de correo electrónico. Haz clic en el botón "saltar esto y utilizar mi correo electrónico existentes". Ahora vas a configurar Mozilla Thunderbird para poder recibir y enviar correo electrónico. Si estás acostumbrado a solamente leer y enviar correo electrónico a través de gmail.com, outlook.com, o yahoo.com, Mozilla Thunderbird será una nueva experiencia, pero no es tan diferente en general.

![](https://ssd.eff.org/files/2016/08/12/021.png)

## Añadiendo una cuenta de correo a Mozilla Thunderbird

Una nueva ventana se abrirá

![](https://ssd.eff.org/files/2016/08/12/022.png)

Ingresa tu nombre, dirección de correo electrónico y la contraseña de tu cuenta de correo electrónico. Mozilla no tiene acceso a tu contraseña o tu cuenta de correo electrónico. Haz clic en el botón "Continuar".

En muchos casos Mozilla Thunderbird detectará automáticamente los ajustes necesarios.

![](https://ssd.eff.org/files/2016/08/12/024.png)

En algunos casos Mozilla Thunderbird no tiene la información completa y deberás introducir algunos parametros de configuración por tu cuenta. Aquí, un ejemplo de las instrucciones que proporciona el propio Google para Gmail:

- Incoming Mail (IMAP) Server - Requires SSL
  - imap.gmail.com
  - Port: 993
  - Requires SSL: Yes
- Outgoing Mail (SMTP) Server - Requires TLS
  - smtp.gmail.com
  - Port: 465 or 587
  - Requires SSL: Yes
  - Requires authentication: Yes
  - Use same settings as incoming mail server
- Nombre Completo o Nombre para mostrar: [tu nombre o seudónimo]
- Nombre de la cuenta o nombre de usuario: tu dirección de Gmail completa ([username@gmail.com](mailto:username@gmail.com)). usuarios de Google Apps, ingresar [username@your_domain.com](mailto:username@your_domain.com)
- Dirección de correo electrónico: la dirección completa de Gmail ([username@gmail.com](mailto:username@gmail.com)) usuarios de Google Apps, por favor, usen [username@your_domain.com](mailto:username@your_domain.com)
- Contraseña: la contraseña de Gmail

Si usas la autenticación de dos factores con Google (y dependiendo de tu modelo de amenaza ¡probablemente deberías!) no puede usar la contraseña estándar de Gmail con Thunderbird. En lugar de ello, será necesario crear una nueva contraseña exclusivamente para que Thunderbird acceda a tu cuenta de Gmail. Ver la [Guía de Google](https://support.google.com/mail/answer/185833?hl=en&rd=1) para hacer esto.

Cuando hayas introducido, correctamente, toda la información, haz clic en el botón "Done".

![](https://ssd.eff.org/files/2016/08/12/025.png)

Mozilla Thunderbird comenzará a descargar copias de tu correo electrónico en tu computadora. Intenta enviar un mensaje de prueba a tus amigos.



## Instalando Enigmail

Enigmail se instala de una forma distinta a Mozilla Thunderbird y GnuPG. Como se ha mencionado antes, Enigmail es un complemento para Mozilla. Haz clic en el botón de "Menú", también llamado el botón hamburguesa y selecciona "Complementos".

![](https://ssd.eff.org/files/2016/08/12/026.png)

Esto te llevará a la pestaña de Administrador de complementos.

![](https://ssd.eff.org/files/2016/08/12/027.png)

Escribe "Enigmail" en el campo de búsqueda de complementos para buscar Enigmail en el sitio web de Complementos de Mozilla.

![](https://ssd.eff.org/files/2016/08/12/028.png)

Enigmail será la primera opción. Haz clic en el botón "Instalar".

![](https://ssd.eff.org/files/2016/08/12/029.png)

![](https://ssd.eff.org/files/2016/08/12/030.png)

Una vez instalado el complemento Enigmail Mozilla Thunderbird te pedirá reiniciar el navegador para activar Enigmail. Haga clic en el botón "Reiniciar ahora" y Mozilla Thunderbird se reiniciará.

![](https://ssd.eff.org/files/2016/08/12/032.png)

Cuando Mozilla Thunderbird se reinicie, se abrirá una ventana adicional que iniciará el proceso de configuración de Enigmail. Selecciona el botón "Iniciar configuración ahora" y haz clic en el botón "Siguiente".

![](https://ssd.eff.org/files/2016/08/12/033.png)

Creemos que la opción "configuración estándar" de Enigmail, es una buena opción. Haz clic en el botón "Siguiente".

Ahora podrás comenzar a crear tu clave privada y la clave pública.

</div>

<div class="field-item odd">

## Creando una clave pública y una clave privada

![](https://ssd.eff.org/files/2016/08/12/034.png)

A menos que ya hayas configurado más de una cuenta de correo electrónico, Enigmail elegirá la cuenta de correo electrónico acabas de configurar. La primera cosa que que necesitas hacer es seleccionar [una frase de contraseña segura](http://ssd.eff.org/en/module/creating-strong-passwords) para su clave privada.

_Haz clic en el botón "Siguiente"._

![](https://ssd.eff.org/files/2016/08/12/035.png)

![](https://ssd.eff.org/files/2016/08/12/036.png)

Tu clave expirará en un momento determinado; cuando esto suceda, la gente dejará de usarla para cifrar cualquier nuevo correo electrónico enviado a ti, sin embargo puede que no recibas advertencia o explicación acerca de por qué. Por lo tanto, es posible que desees marcar tu calendario y prestar atención a este problema un mes antes de la fecha de caducidad.

Es posible extender la vida útil de una clave ya existente, asignadole una nueva y posterior, fecha de vencimiento o es posible sustituirla por una nueva clave mediante la creación de otra nueva desde cero. Ambos procesos pueden requerir contactar a las personas que te escriben y asegurarte de que reciban la clave actualizada; el software actual no es muy competente en la automatización de este proceso. Asi que establece un recordatorio a ti mismo; pero si no crees que serás capaz de lidiar con eso, podrías considerar configurar la clave para que esta nunca expire, aunque en ese caso, otras personas podrían tratar de usarla cuando se comuniquen contigo en un futuro lejano, incluso si tú no tienes más la clave o no usas [PGP![](https://ssd.eff.org/sites/all/themes/ssd/img/info.png)](/es/glossary/pgp "PGP or Pretty Good Privacy was one of the first popular implementations of public key cryptography. Phil Zimmermann, its creator, wrote the program in 1991 to help activists and others protect their communications. He was formally investigated by the US government when the program spread outside the United States. At the time, exporting tools that included strong public key encryption was a violation of US law. PGP continues to exist as a commercial software product. A free implementation of the same underlying standard that PGP uses called GnuPG (or GPG) is also available. Because both use the same interchangeable approach, people will refer to using a “PGP key” or sending a “PGP message”, even if they are using GnuPG. ").

Enigmail generará la clave y vez que esté lista, una pequeña ventana se abrirá pidiendote que generes un certificado de revocación. Es importante contar con este certificado de revocación, ya que te permiten invalidar las clave privada y pública. Es importante, tambien, señalar que la mera eliminación de la clave privada no invalida la clave pública y puede derivar en que otros te escriban correos que no puedan ser descifrados. _Haz clic en el botón "Generar Certificado"._

![](https://ssd.eff.org/files/2016/08/12/037.png)

Primero se te pedirá que proporciones la contraseña que usaste al crear la clave PGP. Haz clic en el botón "OK".

![](https://ssd.eff.org/files/2016/08/12/038.png)

Se abrirá una ventana para ofrecerte un lugar donde guardar el certificado de revocación. Si bien puedes guardar el archivo en el equipo, se recomienda guardarlo en una unidad USB que esté destinada exclusivamente para eso y nada más y almacenar esa unidad en un lugar seguro. También se recomienda eliminar el certificado de revocación del computador donde estén las claves, para evitar la revocación no intencional. Aún mejor, guarda este archivo en un disco encriptado. Elige el lugar donde vas a guardar el archivo y _haz clic en el botón "Guardar"._

![](https://ssd.eff.org/files/2016/08/12/039.png)

Ahora Enigmail te dará más información acerca de cómo guardar el archivo de revocación de certificados de nuevo. _Haz clic en el botón "OK"._

![](https://ssd.eff.org/files/2016/08/12/040.png)

Finalmente, haz terminado de generar las clave privada y pública. _Haz clic en el botón "Finalizar".
