# EFUCVtesis.cls
Es un .cls para facilitar la escritura de tesis de grado adaptadas al formato de la Escuela de Física de la Universidad Central de Venezuela

Para empezar a utilizar el cls, se prueba el ejemplo mi_tesis.tex.

Al compilar mi_tesis se genera mi_tesis.pdf. Así podemos saber si el documento funciona bien en nuestra máquina.

Una vez lograda la prueba se puede escribir el nuevo documento modificando sobre ejemplo mi_tesis.tex.

mi_tesis.tex usa los archivos en la carpeta mi_tesis. Una vez hechas las pruebas, esta carpeta puede ser eliminada. O se puede modificar, incluyendo allí los archivos de interés para el nuevo proyecto.

Todos los documentos requeridos obligatoriamente para el funcionamiento del .cls están en la carpeta EFUCVtesis. Esta carpeta no debe ser borrada.

EFUCVtesis.cls ha funcionado bien en ubuntu, linux-mint y windows. No hay pruebas conocidas en otros sistemas operativos.

EFUCVtesis está basado en book.cls. Requiere los siguientes paquetes:

inputenc [utf8] <- escritura normal en español (acentos y eñes)

babel [spanish] <- idioma del documento

ifthen <- manejar condiciones

mhchem [version=3] <- escritura de fórmulas químicas

environ <- incluir páginas con formato especial

pdfpages <- fondo de portada

eso-pic <- fondo de portada

leading <- variación del interlineado

fancyhdr <- configuración de encabezados y pies de página
