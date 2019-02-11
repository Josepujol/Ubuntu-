# Ubuntu TICII
Listado de programas de los PCs del aula TICII y como instalarlos desde el terminal. 
Sistema operativo Ubuntu 16.04 LTS versión 64 bits

# PARA EMPEZAR

# Actualizaciones
- sudo apt-get update && sudo apt-get dist-upgrade

# Controladores de Hardware
- sudo add-apt-repository ppa:xorg-edgers/ppa
- sudo apt-get update
- sudo apt-get upgrade

# Restricted areas- Flash player
- sudo apt-get install ubuntu-restricted-extras

# libavcodec-extra
- sudo apt-get install libavcodec-extra

# Apariencia
- sudo apt-get install unity-tweak-tool

# PROGRAMAS
# Java
- sudo add-apt-repository ppa:openjdk-r/ppa  
- sudo apt-get update && sudo apt-get install openjdk-7-jdk

# Python
- sudo apt-get update && sudo apt-get install python3

# LibreCAD
- sudo add-apt-repository ppa:librecad-dev/librecad-stable
- sudo apt-get update && sudo apt-get install librecad

# FreeCAD
- sudo add-apt-repository -y ppa:freecad-maintainers/freecad-stable
- sudo apt-get update && sudo apt-get install freecad

# Fritzing
- sudo apt-get update && sudo apt-get install fritzing
- sudo apt-get install graphviz

# Chromiun
- sudo add-apt-repository ppa:a-v-shkop/chromium
- sudo apt-get update && sudo apt-get install chromium-browser

# kdenlive
- sudo apt-add-repository ppa:kdenlive/kdenlive-stable
- sudo apt-get update && sudo apt-get install kdenlive

# VLC
- sudo apt-get update && sudo apt-get install vlc

# Pinta
- sudo add-apt-repository ppa:pinta-maintainers/pinta-stable
- sudo apt-get update && sudo apt-get install pinta

# Inkscape
- sudo apt-get update && sudo apt-get install inkscape

# Gimp
- sudo add-apt-repository ppa:otto-kesselgulasch/gimp
- sudo apt update && sudo apt install gimp

# Actualizar Mozilla
- sudo add-apt-repository ppa:ubuntu-mozilla-security/ppa
- sudo apt-get update
- sudo apt-get upgrade

# Actualizar LibreOffice
- sudo add-apt-repository ppa:libreoffice/ppa 
- sudo apt-get update && sudo apt-get install libreoffice

# Libreria PyGame
- sudo apt-get update && sudo apt-get install python-pygame

# Arduino
- // Descargar ultima versión Arduino desde https://www.arduino.cc/en/Main/Software
- cd Descargas/arduino*	// movernos a la carpeta donde está Arduino
- ./install.sh
- sudo usermod -a -G dialout usuario

# OpenSCAD
- sudo apt-get update && sudo apt-get install openscad

# SimpleScreenrecorder
- sudo add-apt-repository ppa:maarten-baert/simplescreenrecorder
- sudo apt-get update && sudo apt-get install simplescreenrecorder

# Visualino
- sudo add-apt-repository ppa:vrruiz/visualino
- sudo apt-get update && sudo apt-get install visualino

# Bluefish
- sudo apt-get update && sudo apt-get install bluefish

# Audacity
- sudo add-apt-repository ppa:ubuntuhandbook1/audacity
- sudo apt-get update && sudo apt-get install audacity

# Processing
- http://nontenxeito.net/instalar-processing-3-en-ubuntu-con-acceso-directo-desde-launcher/
- // Descargar la ultima version de Processing desde https://processing.org/download/
- sudo chmod +x /opt/
- sudo mv /home/usuario/Descargas/processing /opt/
- sudo gedit /usr/share/applications/processing.desktop

# Snap4Arduino
- // Descargar la ultima version de Snap4Arduino desde http://snap4arduino.rocks/
- sudo chmod +x /opt/
- sudo mv /home/usuario/Descargas/Snap4Arduino /opt/
- sudo cp /opt/Snap4Arduino/Snap4Arduino.desktop  /usr/share/applications/Snap4Arduino.desktop
- sudo gedit /usr/share/applications/Snap4Arduino.desktop

[Desktop Entry]
Type=Application
Version=1.0
Icon=/opt/Snap4Arduino/icons/128x128x32.png
Exec=sh -c 'cd /opt/Snap4Arduino && ./launcher.sh'
Name=Snap4Arduino
Name[en]=Snap4Arduino
GenericName[en]=Use Snap! to control Arduino boards. Arduino goes lambda!

# Cura
- sudo add-apt-repository ppa:thopiekar/cura
- sudo apt-get update && sudo apt-get install cura

# Cura version 3.6
// Descargar version 3.6
// mover a la carpeta donde esta archivo 
chmod u+x Ultimaker_Cura-3.6.0.AppImage 
./Ultimaker_Cura-3.6.0.AppImage

# KiCAD
sudo add-apt-repository --yes ppa:js-reynaud/kicad-5
sudo apt update
sudo apt install kicad
