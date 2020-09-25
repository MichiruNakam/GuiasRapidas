# Librerías Miscelaneas para Linux

## VPN - Cisco Anyconnect 

  Para no tener que utilizar el software propietario de cisco existe una alternativa open-source compatible con cualquier OS basado en linux:
   <strong>Open Connect</strong>
   
    sudo apt install openconnect network-manager-openconnect network-manager-openconnect-gnome
    
  [Guía de uso](https://people.eng.unimelb.edu.au/lucasjb/archive/oc_old.html)
  
## Plank 
  
  Dock personalizable cin íconos al estilo OS.
  Se debe descargar de la página oficial [Descargar aquí](https://pkgs.org/download/plank). 
  Para instalarse se debe instalar como cualquier deb: 

    sudo apt install ./path_to_plank_deb 
    
  Es importante desactivar el dock que trae por defecto gnome. Esto se puede realizar utilizando gnome-tweaks, los cuales vienen por defecto instalados en Ubuntu 20. Si este no es el caso, se puede instalar de la siguiente forma:
  
    sudo apt install gnome-tweaks
    
  Ir a la sección *Extensions* y quitar la pestaña *Ubuntu dock*.
  
 

  
