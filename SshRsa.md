# Guia para usar las llaves rsa por ssh

### Generar llave

`ssh-keygen`
 
### Poner llave en servidor remoto

1. Copiar el texto del archivo `~/.ssh/id_rsa.pub`

2. Iniciar sesión en el servidor remoto

3. Pegar el texto al final del archivo `~/.ssh/autorized_keys`
