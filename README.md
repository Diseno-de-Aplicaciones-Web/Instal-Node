# Instal-Node
Instalacion Node

ir a nodes, 
bajo el cuadro de descarga hay un enlace que pone otras descargas => Pulsamos
descargamos Binario Windows (.zip) 64-bit
descomprimimos la carpeta.
la ponemos en el directorio de GIT del curso y nos quedamos con la ruta 
(pulsamos en la parte superior donde aparece la ruta de carpetas y nos pondrá la ruta tipo... 
C:\Programacion\PortableGit\nodejs) CTRL - D
abrir cmd y escribir
rundll32 sysdm.cpl,EditEnvironmentVariables
damos a Path => Nuevo => CTRL - V (La ruta que teníamos)
añadimos el path donde tenemos nodes. en mi caso... C:\Programacion\PortableGit\nodejs
abrimos powershell y probamos que funciona con:
node -v
npm -v
