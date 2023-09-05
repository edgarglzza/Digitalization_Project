README
DitigalizationProject 1.0.0 -- 04/09/2023
by Edgar Federico González Aguirre

Este es un programa habilitado para windows 10.
Desarrollado en Python 3.11
Entorno: Tkinter, Reportlab, Platypus.
_________________________________________________________
INSTALACION
1. Colocar toda la carpeta en Documentos llamada como tu
preferencia (SERVINORTE, por ejemplo).
2. Abrir la carpeta dist y dar doble click en el .exe
_________________________________________________________
DESCRIPCION
Este programa es un intento para solucionar el error
humano en la captura de datos, este software tiene como
finalidad evitar utilizar softwares terceros (como
excel / macros) para la captura de datos. Haciendo más
práctico el manejo y registro de la información y
enfocandose el usuario solamente en la recepción de
equipos de costura y etiquetarlos, conociendo así: su
número de orden, ficha, fecha de recepción, etc.
_________________________________________________________
USO DEL PROGRAMA
Al ejecutarse, registrar todos los datos en los campos
correspondientes (nombre, tel1, tel2, etc); para los
checkboxes, dar click a aquellos objetos/características
faltantes del equipo y posterior seleccionar el tipo de
equipo (ej. Casero, costura); por último, asignar la
ficha, verificar la fecha y escribir el servicio dado
(reparación, mantenimiento) con su costo (300). A con-
tinuación, una breve explicación de los 3 botones:

- Guardar: guarda el registro en un CSV a manera de 
  historial. Sirve para poder general el PDF posterior-
  mente.

- Imprimir: Genera una ventana dando las opciones: 
  Cancelar (cancela la acción, cierra la ventana), ver
  archivo (genera la orden actual en PDF y muestra su
  ubicación en el explorador de archivos) e Imprimir
  (realiza el comando de imprimir a la impresora pre-
  determinada).

- Nueva ODT (orden de trabajo): borra todos los datos
  actuales, sirve para escribir de nuevo otra orden sin
  necesidad de borar campo por campo.

NOTA.
Es importante dar click en el botón de GUARDAR para
poder imprimir o visualizar el PDF de la orden de trabajo
debido a que registra los útlimos datos guardados.
___________________________________________________________
TRABAJOS POSTERIORES

- Registro a una base de datos SQL.
- API para agenda a domicilio.
- Generación de certificado por uso de equipo.
- Nota de venta.
- Facturación CFDI.
- Generación de diccionario/índice de productos (prioritario)
  una especie de buscador que indique el producto, imágen,
  descripción, ubicación, etc.
