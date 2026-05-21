---
title: "EmfPlusBitmapData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusBitmapData especifica una imagen de mapa de bits con datos de píxeles."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusBitmapData extends EmfPlusBaseBitmapData
```

El objeto EmfPlusBitmapData especifica una imagen de mapa de bits con datos de píxeles.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getColors()](#getColors--) | Obtiene o establece los colores de la paleta Colors (variable): un objeto opcional `EmfPlusPalette` (sección 2.2.2.28), que especifica la paleta de colores utilizada en los datos de píxeles. |
| [setColors(EmfPlusPalette value)](#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Obtiene o establece los colores de la paleta Colors (variable): un objeto opcional `EmfPlusPalette` (sección 2.2.2.28), que especifica la paleta de colores utilizada en los datos de píxeles. |
| [getPixelData()](#getPixelData--) | Obtiene o establece los datos de píxeles PixelData (variable): una matriz de bytes que especifica los datos de píxeles. |
| [setPixelData(byte[] value)](#setPixelData-byte---) | Obtiene o establece los datos de píxeles PixelData (variable): una matriz de bytes que especifica los datos de píxeles. |
### EmfPlusBitmapData() {#EmfPlusBitmapData--}
```
public EmfPlusBitmapData()
```


### getColors() {#getColors--}
```
public EmfPlusPalette getColors()
```


Obtiene o establece los colores de la paleta Colors (variable): un objeto opcional `EmfPlusPalette` (sección 2.2.2.28), que especifica la paleta de colores utilizada en los datos de píxeles. Este campo DEBE estar presente si la bandera I está establecida en el campo PixelFormat del objeto `EmfPlusBitmap`.

Valor: Los colores.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setColors(EmfPlusPalette value) {#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setColors(EmfPlusPalette value)
```


Obtiene o establece los colores de la paleta Colors (variable): un objeto opcional `EmfPlusPalette` (sección 2.2.2.28), que especifica la paleta de colores utilizada en los datos de píxeles. Este campo DEBE estar presente si la bandera I está establecida en el campo PixelFormat del objeto `EmfPlusBitmap`.

Valor: Los colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

### getPixelData() {#getPixelData--}
```
public byte[] getPixelData()
```


Obtiene o establece los datos de píxeles PixelData (variable): una matriz de bytes que especifica los datos de píxeles. El tamaño y formato de estos datos pueden calcularse a partir de los campos del objeto EmfPlusBitmap, incluido el formato de píxel de la enumeración `Consts.EmfPlusPixelFormat` (sección 2.1.1.25).

Valor: Los datos de píxeles.

**Returns:**
byte[]
### setPixelData(byte[] value) {#setPixelData-byte---}
```
public void setPixelData(byte[] value)
```


Obtiene o establece los datos de píxeles PixelData (variable): una matriz de bytes que especifica los datos de píxeles. El tamaño y formato de estos datos pueden calcularse a partir de los campos del objeto EmfPlusBitmap, incluido el formato de píxel de la enumeración `Consts.EmfPlusPixelFormat` (sección 2.1.1.25).

Valor: Los datos de píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

