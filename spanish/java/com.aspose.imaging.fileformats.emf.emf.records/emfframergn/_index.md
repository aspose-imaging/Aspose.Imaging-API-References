---
title: "EmfFrameRgn"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_FRAMERGN dibuja un borde alrededor de la región especificada usando el pincel especificado."
type: docs
weight: 62
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfframergn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFrameRgn extends EmfDrawingRecordType
```

El registro EMR\_FRAMERGN dibuja un borde alrededor de la región especificada usando el pincel especificado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfFrameRgn(EmfRecord source)](#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfFrameRgn`. |
| [EmfFrameRgn()](#EmfFrameRgn--) | Inicializa una nueva instancia de la clase [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que especifica el rectángulo delimitador. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que especifica el rectángulo delimitador. |
| [getRgnDataSize()](#getRgnDataSize--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región, en bytes. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región, en bytes. |
| [getIhBrush()](#getIhBrush--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la tabla de objetos EMF del pincel. |
| [setIhBrush(int value)](#setIhBrush-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la tabla de objetos EMF del pincel. |
| [getWidth()](#getWidth--) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho del trazo vertical del pincel, en unidades lógicas. |
| [setWidth(int value)](#setWidth-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho del trazo vertical del pincel, en unidades lógicas. |
| [getHeight()](#getHeight--) | Obtiene o establece un entero con signo de 32 bits que especifica la altura del trazo horizontal del pincel, en unidades lógicas. |
| [setHeight(int value)](#setHeight-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la altura del trazo horizontal del pincel, en unidades lógicas. |
| [getRgnData()](#getRgnData--) | Obtiene o establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData, en unidades lógicas |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Obtiene o establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData, en unidades lógicas |
### EmfFrameRgn(EmfRecord source) {#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFrameRgn(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfFrameRgn`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfFrameRgn() {#EmfFrameRgn--}
```
public EmfFrameRgn()
```


Inicializa una nueva instancia de la clase [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn).

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que especifica el rectángulo delimitador.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que especifica el rectángulo delimitador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región, en bytes.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región, en bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la tabla de objetos EMF del pincel.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la tabla de objetos EMF del pincel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene o establece un entero con signo de 32 bits que especifica el ancho del trazo vertical del pincel, en unidades lógicas.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el ancho del trazo vertical del pincel, en unidades lógicas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene o establece un entero con signo de 32 bits que especifica la altura del trazo horizontal del pincel, en unidades lógicas.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la altura del trazo horizontal del pincel, en unidades lógicas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Obtiene o establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData, en unidades lógicas

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Obtiene o establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData, en unidades lógicas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

