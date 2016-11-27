# script_svxlink
INSTRUCCIONE PARA INSTALAR EL SCRIPT

Desde la consola de linux entrar los siguientes comandos:

sudo apt-get install git

git clone https://github.com/ea3eiz/script_svxlink/

sudo chmod 777 -R script_svxlink

cd script_svxlink

sudo ./svxlink_ea3eiz

Sigue las instrucciones del menú del script




   ************************************************
   *  MENU PARA INSTALAR SVXLINK 15.11 EN UBUNTU  *
   *                      EA3EIZ                  *
   ************************************************

   1) Actualizar Dispositivo (update y upgrade)
   
   2) Instalar svxlink 15.11
   
   3) Editar el fichero ModuleEchoLink.conf
   
   4) Editar el fichero svxlink.conf

   x)  Para Salir

   Por favor, elige una opcion... 1, 2, 3, 4,  x
   
----------------------------------------------------




Cuando termines de usar el menú, lanza el svxlink como:

sudo svxlink

Si te arojara el error while loading shared libraries: libasynccpp.so.1.4

Ejecuta el comando siguiente y se solucionará el error mencionado:

sudo ldconfig -v


