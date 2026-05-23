---
title: "Enumeración DibBitCount"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/
---

La enumeración BitCount especifica el número de bits que definen cada píxel y<br/>                el número máximo de colores en un mapa de bits independiente del dispositivo (DIB).

**Module:** [aspose.imaging.apsbuilder.dib](/imaging/python-net/aspose.imaging.apsbuilder.dib/)

**Full Name:** aspose.imaging.apsbuilder.dib.DibBitCount

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| BITCOUNT0 | El número de bits por píxel no está definido.<br/>                La imagen DEBE estar en formato JPEG o PNG.<br/>                Ninguno de estos formatos incluye una tabla de colores, por lo que este valor<br/>                indica que no hay tabla de colores presente. Consulte [JFIF] y [RFC2083]<br/>                para obtener más información sobre los formatos de compresión JPEG y PNG. |
| BITCOUNT1 | La imagen se especifica con dos colores. Cada píxel en el mapa de bits está<br/>                representado por un solo bit. Si el bit está apagado, el píxel se<br/>                muestra con el color de la primera entrada en la tabla de colores;<br/>                si el bit está encendido, el píxel tiene el color de la segunda entrada en la tabla. |
| BITCOUNT2 | La imagen se especifica con un máximo de 16 colores.<br/>                Cada píxel en el mapa de bits está representado por un índice de 4 bits en la<br/>                tabla de colores, y cada byte contiene 2 píxeles. |
| BITCOUNT3 | La imagen se especifica con un máximo de 256 colores.<br/>                Cada píxel en el mapa de bits está representado por un índice de 8 bits en la<br/>                tabla de colores, y cada byte contiene 1 píxel. |
| BITCOUNT4 | La imagen se especifica con un máximo de 2^16 colores.<br/>                Cada píxel en el mapa de bits está representado por un valor de 16 bits |
| BITCOUNT5 | El mapa de bits tiene un máximo de 2^24 colores, y el campo Colors del DIB es NULL.<br/>                Cada triplete de 3 bytes en la matriz del mapa de bits representa las intensidades relativas<br/>                de azul, verde y rojo, respectivamente, para un píxel. La tabla de colores Colors<br/>                se utiliza para optimizar los colores usados en dispositivos basados en paleta, y DEBE contener<br/>                el número de entradas especificado por el campo ColorUsed del objeto BitmapInfoHeader |
| BITCOUNT6 | El mapa de bits tiene un máximo de 2^24 colores |
