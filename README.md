# Guia

GUIA DE INSTALACION DEL FACTURADOR:
PASO 1: Como primer paso instalaremos el LARAGON, acá se les proporcionara el link de descarga https://laragon.org/download/index.html
 Una vez dentro del sitio web no aparecerá DOWNLOAD LARAGON - FULL (173MB)
 
![image](https://github.com/Jysn22/Guia/assets/125273441/820b8ffb-e66f-4905-9055-bcfc7201da12)

Al dar al botón comenzara la instalación este proceso puede tardar un momento dependiendo de la PC

PASO 2: Una vez instalado el programa lo abrimos y nos aparecerá un panel nos dirigimos al apartado de MENU se nos desplegara un cuadro e iremos a PHP luego se desplegarán varias opciones y daremos click a SOAP 

![image](https://github.com/Jysn22/Guia/assets/125273441/e84178ea-d4a4-4033-946c-aeb9a477e840)

Luego iremos a la tuerquita de (Ajustes) que está en el mismo panel de Laragon lo que haremos es darle la ruta de la instalación del facturador en nuestro pc nos vamos al apartado de ROOT DOCUMENTOS, en la cual escogeremos la ruta de LARAGON y la carpeta de nombre WWW y finalmente le cambios lo que es el HOSTANAME, solo agregaremos al final .pe

![image](https://github.com/Jysn22/Guia/assets/125273441/b8f2ec88-0cd9-4c17-9eb0-a47216934148)

PASO 3: Ahora entraremos a la terminal desde LARAGON, para esto le damos a Iniciar Todo y luego le dan en el botón de terminal.

![image](https://github.com/Jysn22/Guia/assets/125273441/efddf6e6-ea3f-47ee-b085-854b354cfcb1)

Una vez dentro de la terminal de LARAGON lo que haremos será clonar el repositorio del facturador para así tener las carpetas y el contenido para clonar el repositorio pondremos el comando (git clone) seguido del enlace que copiamos en el repositorio de Git Hub del facturador 

![image](https://github.com/Jysn22/Guia/assets/125273441/520a79ac-0866-4911-8d10-2412c7a37e1e)

PASO 4: Luego de que allá terminado la descarga de la carpeta del facturador comenzaremos con los códigos ponemos el comando COMPOSER INSTALL, esperamos a que los codigos carguen en su curso luego actualizamos composer con UPDATE COMPOSER.

![image](https://github.com/Jysn22/Guia/assets/125273441/b0f0f8dc-cf70-499b-a7e0-0e5a509abd08)

![image](https://github.com/Jysn22/Guia/assets/125273441/44c8a770-9770-4246-bceb-e44e75e828e9)


PASO 5: Esperamos a que cargue los comando, seguimos con la instalación el siguiente comando es COMPOSER SELF.UPDATE, luego vamos a poner RM COMPOSER.LOCK, luego COMPOSER INSTALL y luego pondremos GIT CHECKOUT

![image](https://github.com/Jysn22/Guia/assets/125273441/b0f102bb-7d72-4e03-8a09-4fc4964f713a)

Paso 6: Cuando los todos los comandos ya se ejecutarán iremos al panel de control de LARAGON y crearemos una nueva base de datos nos dirigimos al panel de control en el arte de abajo aparecerá BASE DE DATOS le damos click luego le damos nuevamente click en donde dice nueva base de datos y le ponemos de nombre (tenancy) 

![image](https://github.com/Jysn22/Guia/assets/125273441/b65f9c03-78e3-4406-8117-874aa88d4f1d)

Luego volvemos al menú de inicio de LAGARON y elegimos la opción que dice Root, se nos abrirá nuestra carpeta, entramos a la carpeta que dice facturadorpro4, luego buscamos el archivo que se llama (.env.example) y lo copiamos y pegamos ahí mismo el archivos que copiamos pero le vamos a cambiar el nombre, el cual será (.env) y luego clic derecho al archivo y lo editamos en la opción (Edit With Notepad++) una vez adentro lo único que haremos es ir a la línea 5 del código y cambiar la palabra (facturador a facturador4.pe) y le damos en guardar

![image](https://github.com/Jysn22/Guia/assets/125273441/9eb3e0a5-de92-4e0f-aaf2-f3e264981465)

![image](https://github.com/Jysn22/Guia/assets/125273441/adfb258c-d793-48fa-a60d-85354a2d86e9)

Paso 7: Lo siguiente que haremos es seguir pegando códigos, los siguientes códigos serán (php artisan key:generate, composer dump-autoload, php artisan migrate –seed) y luego php artisan storage:link

![image](https://github.com/Jysn22/Guia/assets/125273441/6c9851bf-9e73-4e53-a36b-a3b78eef5e0a)

Paso 8: Ya para terminar finalizamos el LARAGON dando click a detener el programa y luego a iniciar para actualizar todo lo que hemos agregado, luego le damos clic en la opción H que sale arriba para ver si se ha guardado los cambios, luego vamos a buscar la siguiente ruta en nuestra explorador de archivos, disco C, Windows, es-ES, System 32, Drivers, etc. y luego host, aquí le damos en clic derecho luego en propiedades, le desactivamos la opción que dice solo lectura y le damos en continuar, luego cerramos y volvemos al Laragon donde le vamos a volver a entrar en H y tenemos que tenemos lo siguientes códigos

![image](https://github.com/Jysn22/Guia/assets/125273441/0befe5a0-7c61-4b7a-84df-2e67e93589ba)

![image](https://github.com/Jysn22/Guia/assets/125273441/78cfa46a-e539-4250-bb40-976a7cd153e7)

Y para terminar si lo hicimos bien todos los pasos vamos a nuestro explorador de internet favorito y escribiremos facturadorpro4, nos saldrá un login donde nos registraremos el cual pondremos de nombre de usuario admin y la contraseña será 123456 y así lograremos ingresar al facturador.

![Uploading image.png…]()

