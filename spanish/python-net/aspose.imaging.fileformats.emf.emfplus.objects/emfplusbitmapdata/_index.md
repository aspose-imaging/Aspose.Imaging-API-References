---
title: "Clase EmfPlusBitmapData"
type: docs
weight: 60
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---

**Summary:** The EmfPlusBitmapData object specifies a bitmap image with pixel data.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmapData

**Inheritance:** EmfPlusBaseBitmapData

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData__1) | Inicializa una nueva instancia de la clase EmfPlusBitmapData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| colors | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | Obtiene o establece los colores de la paleta <br/>            Colors (variable): Un objeto opcional [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) (sección 2.2.2.28), que especifica la paleta<br/>            de colores utilizada en los datos de píxeles. Este campo DEBE estar presente si la bandera I está establecida en el campo PixelFormat del<br/>            objeto [EmfPlusBitmap](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/). |
| pixel_data | System.Byte | r/w | Obtiene o establece los datos de píxeles <br/>            PixelData (variable): Una matriz de bytes que especifica los datos de píxeles. El tamaño y formato de estos datos pueden ser<br/>            calculados a partir de los campos del objeto EmfPlusBitmap, incluyendo el formato de píxel de la<br/>            enumeración [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) (sección 2.1.1.25). |


### Constructor: EmfPlusBitmapData() {#EmfPlusBitmapData__1}


```
 EmfPlusBitmapData() 
```

Inicializa una nueva instancia de la clase EmfPlusBitmapData

