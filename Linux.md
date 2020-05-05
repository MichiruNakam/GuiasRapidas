# Comandos útiles en Linux

## Reemplazar todas las ocurrencias de un string por otro string en un archivo
  `sed -i 's/{texto_a_reemplazar}/{texto_nuevo}/g' {nombre_de_archivo}`
## Listar recursivamente el contenido del directorio actual
`ls -R`
## Número de archivos en un directorio
`ls -1 | wc -l`

## Ver el encoding de un archivo
`file -bi <file name>`
