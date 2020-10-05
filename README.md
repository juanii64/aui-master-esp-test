### Proyecto que solo acepta parches
Este proyecto no se desarrolla activamente pero * aceptará * solicitudes de extracción.

<h1 align = "center">
  <a href=https://www.archlinux.org/> Archlinux </a> Ultimate Installer
</h1>
<h4 align = "center"> ¡La instalación y configuración de archlinux nunca ha sido tan fácil! </h4>

<p align = "centro">
  <img src = "https://img.shields.io/badge/Maintained%3F-Yes-green?style=for-the-badge">
  <img src = "https://img.shields.io/github/license/helmuthdu/aui?style=for-the-badge">
  <img src = "https://img.shields.io/github/issues/helmuthdu/aui?color=violet&style=for-the-badge">
  <img src = "https://img.shields.io/github/stars/helmuthdu/aui?style=for-the-badge">
  <img src = "https://img.shields.io/github/forks/helmuthdu/aui?color=teal&style=for-the-badge">
</p>

## Nota
* Primero puedes probarlo en una `VirtualMachine`

## Requisitos previos

- Una conexión a Internet que funcione
- Iniciar sesión como 'root'

## Obtención del repositorio
### Con git
- Aumentar la partición del espacio para las vacas: `mount -o remount, size = 2G / run / archiso / cowspace`
- Obtener la lista de paquetes e instalar git: `pacman -Sy git`
- Obtener el script: `git clone git: // github.com / helmuthdu / aui`

### Sin git
- Aumentar la partición del espacio para las vacas: `mount -o remount, size = 2G / run / archiso / cowspace`
- Obtenga el script: `wget https://github.com/helmuthdu/aui/tarball/master -O - | alquitrán xz`
    - una URL alternativa (para escribir menos (github shorten)) es `wget https://git.io/vS1GH -O - | alquitrán xz`
    - una URL alternativa (para escribir menos) es `wget http://bit.ly/NoUPC6 -O - | alquitrán xz`
    - super corto `wget ow.ly/wnFgh -O aui.zip`

## Cómo utilizar
- FIFO [Base del sistema]: `cd aui; . / Fifo`
- LILO [El resto]: `cd aui; . / lilo`

## Caracteristicas
### GUIÓN FIFO
- Configurar mapa de teclas
- Seleccionar editor
- Lista de espejos de configuración automática
- Crear partición
- Formatear dispositivo
- Instalar la base del sistema
- Configurar fstab
- Configurar nombre de host
- Configurar zona horaria
- Configurar reloj de hardware
- Configurar la configuración regional
- Configurar mkinitcpio
- Instalar / Configurar el cargador de arranque
- Configurar lista de espejos
- Configurar contraseña de root

### GUIÓN DE LILO
- Copia de seguridad de todos los archivos modificados
- Instalar repositorios adicionales
- Crear y configurar un nuevo usuario
- Instalar y configurar sudo
- Servicios de habilitación automática en systemd
- Instale un AUR Helper [trizen, yay ...]
- Instalar el sistema base
- Instalar systemd
- Instalar precarga
- Instalar Zram
- Instalar Xorg
- Instalar controladores de GPU
- Instalar CUPS
- Instalar firmwares inalámbricos / bluetooth adicionales
- Asegurar el acceso a GIT a través de un firewall
- Instale DE o WM [Cinnamon, Enlightenment, FluxBox, GNOME, i3, KDE, LXDE, OpenBox, XFCE ...]
- Instalar herramientas de desarrollo [Vim, Emacs, Eclipse ...]
- Instale aplicaciones de Office [LibreOffice, GNOME-Office, Latex ...]
- Instalar herramientas del sistema [Wine, Virtualbox, Grsync, Htop ...]
- Instalar aplicaciones de gráficos [Inkscape, Gimp, Blender, MComix ...]
- Instalar aplicaciones de Internet [Firefox, Google-Chrome, Jdownloader ...]
- Instalar aplicaciones multimedia [Rhythmbox, Clementine, Codecs ...]
- Instalar juegos [Desura, PlayOnLinux, Steam, Minecraft ...]
- Instalar fuentes [Liberation, MS-Fonts, Google-webfonts ...]
- Instalar y configurar servidores web
- Y muchos más...


## Gracias helmuthdu
Si le gusta mi trabajo, considere una pequeña donación de Paypal en helmuthdu@gmail.com :)

## Licencia: scroll:
Este proyecto tiene la licencia GNU General Public License V3. Para obtener más información, consulte el archivo `LICENSE` o visite https://www.gnu.org/licenses/gpl-3.0.en.html.