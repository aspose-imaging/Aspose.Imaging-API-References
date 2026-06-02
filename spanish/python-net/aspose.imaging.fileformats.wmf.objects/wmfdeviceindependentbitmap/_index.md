---
title: "Clase WmfDeviceIndependentBitmap"
type: docs
weight: 180
url: /es/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---

**Summary:** The DeviceIndependentBitmap Object defines an image in<br/>                device-independent bitmap (DIB) format

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap__1) | Inicializa una nueva instancia de la clase WmfDeviceIndependentBitmap |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| a_data | System.Byte | r/w | Obtiene o establece una matriz de bytes que define la imagen. El tamaño y<br/>                formato de estos datos se determina mediante la información en el<br/>                campo DIBHeaderInfo. |
| cached_image | System.Byte | r/w | Obtiene o establece la imagen rasterizada en caché. |
| colors_data | System.Byte | r/w | Obtiene o establece una matriz opcional de ya sea objetos RGBQuad (sección<br/>                2.2.2.20) o enteros sin signo de 16 bits que definen una tabla de colores. El<br/>                tamaño y contenido de este campo DEBERÍA determinarse a partir del<br/>                registro o objeto metafile que contiene este DeviceIndependentBitmap<br/>                y de la información en el campo DIBHeaderInfo. Consulte la enumeración ColorUsage<br/>                (sección 2.1.1.6) y la enumeración BitCount (sección<br/>                2.1.1.3) para obtener detalles adicionales. |
| header | [WmfBitmapBaseHeader](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) | r/w | Obtiene o establece ya sea un objeto BitmapCoreHeader (sección 2.2.2.2) o un<br/>                objeto BitmapInfoHeader (sección 2.2.2.3) que especifica información<br/>                sobre la imagen |


### Constructor: WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap__1}


```
 WmfDeviceIndependentBitmap() 
```

Inicializa una nueva instancia de la clase WmfDeviceIndependentBitmap

