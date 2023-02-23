# Demo_PIOTR.GO_888_DVI
This code creates a bidimensional pattern whoing us a 888 screen.

We use in this pattern the MAX100O with de I/O Board ATLAS.
You can see with this example de deep colour that DVI could reach.
Doing in a diferencial pairs -> 8 pins has his drawbacks but other way you need more than 26 signals for a 24 bit VGA.

Se muestra en la placa max1000 con ATLAS, la profundidad de color que puede obtener un HDMI/DVI con una profuncidad 888 en vga mínimo serían 26 pines dos para sincronismo vertical y horizontal y 24 para la profundidad de color comparados con los 8 necesarios en un DVI/HDMI directo.

The original demo used in Linchee Tang:
EL ejercicio/demo original:
https://github.com/piotr-go/Lichee-Tang/tree/master/VGA

You could change the fpga chip to cyclone 10LP and use pinplaner to change the defaults pins of the design.
Se puede pasar a CYC1000/ATLAS cambiando el integrado fpga y la asignación de pines.


Los fuentes para max1000/ATLAS:


