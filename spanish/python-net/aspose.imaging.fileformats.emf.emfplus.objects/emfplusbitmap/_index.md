---
title: "Clase EmfPlusBitmap"
type: docs
weight: 50
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---

**Summary:** The EmfPlusBitmap object specifies a bitmap that contains a graphics image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmap

**Inheritance:** EmfPlusBaseImageData

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusBitmap()](#EmfPlusBitmap__1) | Inicializa una nueva instancia de la clase EmfPlusBitmap |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bitmap_data | [EmfPlusBaseBitmapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata/) | r/w | Obtiene o establece los datos del mapa de bits<br/>            BitmapData (variable): Datos de longitud variable que definen el objeto de datos del mapa de bits especificado en el campo Type. El<br/>            contenido y formato de los datos pueden ser diferentes para cada tipo de mapa de bits. |
| height | int | r/w | Obtiene o establece la altura del mapa de bits<br/>            Height (4 bytes): Un entero con signo de 32 bits que especifica la altura en píxeles del área ocupada por el mapa de bits.<br/>            Si la imagen está comprimida, según el campo Type, este valor es indefinido y DEBE ser ignorado. |
| pixel_format | [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) | r/w | Obtiene o establece el formato de píxel<br/>            PixelFormat (4 bytes): Un entero sin signo de 32 bits que especifica el formato de los píxeles que componen la imagen del mapa de bits.<br/>            Los formatos de píxel compatibles se especifican en la enumeración [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) (sección<br/>            2.1.1.25).<br/>            Si la imagen está comprimida, según el campo Type, este valor es indefinido y DEBE ser ignorado. |
| stride | int | r/w | Obtiene o establece el stride de la imagen<br/>            Stride (4 bytes): Un entero con signo de 32 bits que especifica el desplazamiento en bytes entre el comienzo de una línea de escaneo y<br/>            la siguiente. Este valor es el número de bytes por píxel, que se especifica en el campo PixelFormat, multiplicado por<br/>            el ancho en píxeles, que se especifica en el campo Width. El valor de este campo DEBE ser múltiplo de cuatro.<br/>            Si la imagen está comprimida, según el campo Type, este valor es indefinido y DEBE ser ignorado. |
| type | [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) | r/w | Obtiene o establece el tipo de la imagen<br/>            Type (4 bytes): Un entero sin signo de 32 bits que especifica el tipo de datos en el campo BitmapData. Este valor DEBE<br/>            estar definido en la enumeración [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) (sección 2.1.1.2). |
| width | int | r/w | Obtiene o establece el ancho de la imagen<br/>            Width (4 bytes): Un entero con signo de 32 bits que especifica el ancho en píxeles del área ocupada por el mapa de bits.<br/>            Si la imagen está comprimida, según el campo Type, este valor es indefinido y DEBE ser ignorado. |


### Constructor: EmfPlusBitmap() {#EmfPlusBitmap__1}


```
 EmfPlusBitmap() 
```

Inicializa una nueva instancia de la clase EmfPlusBitmap

