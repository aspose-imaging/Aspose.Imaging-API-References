---
title: "EmfSetPixelV"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETPIXELV define el color del píxel en las coordenadas lógicas especificadas."
type: docs
weight: 135
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSetPixelV extends EmfDrawingRecordType
```

El registro EMR\_SETPIXELV define el color del píxel en las coordenadas lógicas especificadas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetPixelV(EmfRecord source)](#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetPixelV`. |
| [EmfSetPixelV()](#EmfSetPixelV--) | Inicializa una nueva instancia de la clase [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPixel()](#getPixel--) | Obtiene o establece un objeto WMF PointL de 64 bits ([MS-WMF] sección 2.2.2.15) que especifica las coordenadas lógicas del píxel. |
| [setPixel(Point value)](#setPixel-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL de 64 bits ([MS-WMF] sección 2.2.2.15) que especifica las coordenadas lógicas del píxel. |
| [getArgb32Color()](#getArgb32Color--) | Obtiene o establece un objeto WMF ColorRef de 32 bits ([MS-WMF] sección 2.2.8) que especifica el color del píxel. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Obtiene o establece un objeto WMF ColorRef de 32 bits ([MS-WMF] sección 2.2.8) que especifica el color del píxel. |
### EmfSetPixelV(EmfRecord source) {#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPixelV(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetPixelV`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfSetPixelV() {#EmfSetPixelV--}
```
public EmfSetPixelV()
```


Inicializa una nueva instancia de la clase [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv).

### getPixel() {#getPixel--}
```
public Point getPixel()
```


Obtiene o establece un objeto WMF PointL de 64 bits ([MS-WMF] sección 2.2.2.15) que especifica las coordenadas lógicas del píxel.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setPixel(Point value) {#setPixel-com.aspose.imaging.Point-}
```
public void setPixel(Point value)
```


Obtiene o establece un objeto WMF PointL de 64 bits ([MS-WMF] sección 2.2.2.15) que especifica las coordenadas lógicas del píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Obtiene o establece un objeto WMF ColorRef de 32 bits ([MS-WMF] sección 2.2.8) que especifica el color del píxel.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Obtiene o establece un objeto WMF ColorRef de 32 bits ([MS-WMF] sección 2.2.8) que especifica el color del píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

