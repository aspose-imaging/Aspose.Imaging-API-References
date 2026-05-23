---
title: "Clase WmfBitmapInfoHeader"
type: docs
weight: 70
url: /es/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---

**Summary:** The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent<br/>                bitmap (DIB).

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfBitmapInfoHeader

**Inheritance:** WmfBitmapBaseHeader

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader__1) | Inicializa una nueva instancia de la clase WmfBitmapInfoHeader |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| STRUCTURE_SIZE [static] | int | r | El tamaño de la estructura |
| bit_count | [DibBitCount](/imaging/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/) | r/w | Obtiene o establece un entero sin signo de 16 bits que define el formato de<br/>                cada píxel, y el número máximo de colores en el DIB. Este valor<br/>                DEBE estar en la enumeración [WmfBitmapBaseHeader.bit_count](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) (sección 2.1.1.3). |
| color_important | int | r/w | Obtiene o establece un entero sin signo de 32 bits que define el número de índices de color que se requieren para mostrar<br/>                el DIB.<br/>                Si este valor es cero, se requieren todos los índices de color |
| color_used | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de índices en la tabla de colores utilizada por el DIB, como<br/>                sigue:<br/>                Si este valor es cero, el DIB usa el número máximo de colores que corresponde al valor BitCount.<br/>                Si este valor es distinto de cero y el valor BitCount es menor que 16, este valor especifica el número de colores usados por<br/>                el DIB.<br/>                Si este valor es distinto de cero y el valor BitCount es 16 o mayor, este valor especifica el tamaño de la tabla de colores<br/>                utilizada para optimizar el rendimiento de la paleta del sistema.<br/>                Nota Si este valor es distinto de cero y mayor que el tamaño máximo posible de la tabla de colores basado en el valor BitCount<br/>                el tamaño máximo de la tabla de colores DEBE asumirse. |
| compression | [WmfCompression](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/) | r/w | Obtiene o establece un entero sin signo de 32 bits que define el modo de compresión del DIB. Este valor DEBE estar en la<br/>                Enumeración Compression (sección 2.1.1.7).<br/>                Este valor NO DEBE especificar un formato comprimido si el DIB es un mapa de bits de arriba hacia abajo, como lo indica el valor Height. |
| header_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que define el tamaño de este<br/>                objeto, en bytes. |
| height | int | r/w | Obtiene o establece un entero con signo de 32 bits que define la altura del DIB, en píxeles. Este valor NO DEBE ser cero.<br/>                Si este valor es positivo, el DIB es un mapa de bits de abajo hacia arriba, y su origen es la esquina inferior izquierda.<br/>                Si este valor es negativo, el DIB es un mapa de bits de arriba hacia abajo, y su origen es la esquina superior izquierda. Los mapas de bits de arriba hacia abajo<br/>                no admiten compresión.<br/>                Este campo DEBERÍA especificar la altura del archivo de imagen descomprimido, si el valor Compression especifica formato JPEG o PNG<br/>                . |
| image_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que define el tamaño, en bytes, de la imagen.<br/>                Si el valor Compression es BI_RGB, este valor DEBERÍA ser cero y DEBE ser ignorado.<br/>                Si el valor Compression es BI_JPEG o BI_PNG, este valor DEBE especificar el tamaño del búfer de imagen JPEG o PNG,<br/>                respectivamente. |
| planes | int | r/w | Obtiene o establece un entero sin signo de 16 bits que define el número de<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) para el dispositivo de destino. Este valor DEBE ser<br/>                0x0001. |
| width | int | r/w | Obtiene o establece un entero con signo de 32 bits que define el ancho del DIB, en píxeles. Este valor DEBE ser positivo.<br/>                Este campo DEBERÍA especificar el ancho del archivo de imagen descomprimido, si el valor Compression especifica formato JPEG o PNG<br/>                . |
| x_pels_per_meter | int | r/w | Obtiene o establece un entero con signo de 32 bits que define la resolución horizontal, en píxeles por metro, del dispositivo<br/>                objetivo para el DIB |
| y_pels_per_meter | int | r/w | Obtiene o establece un entero con signo de 32 bits que define la resolución vertical, en píxeles por metro, del dispositivo<br/>                objetivo para el DIB |


### Constructor: WmfBitmapInfoHeader() {#WmfBitmapInfoHeader__1}


```
 WmfBitmapInfoHeader() 
```

Inicializa una nueva instancia de la clase WmfBitmapInfoHeader

