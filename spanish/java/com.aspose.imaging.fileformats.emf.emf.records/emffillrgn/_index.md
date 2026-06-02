---
title: "EmfFillRgn"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_FILLRGN rellena la región especificada usando el pincel especificado."
type: docs
weight: 59
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillRgn extends EmfDrawingRecordType
```

El registro EMR\_FILLRGN rellena la región especificada usando el pincel especificado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfFillRgn(EmfRecord source)](#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfFillRgn`. |
| [EmfFillRgn()](#EmfFillRgn--) | Inicializa una nueva instancia de la clase `EmfFillRgn`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador. |
| [getRgnDataSize()](#getRgnDataSize--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región, en bytes. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región, en bytes. |
| [getIhBrush()](#getIhBrush--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la tabla de objetos EMF del pincel para rellenar la región. |
| [setIhBrush(int value)](#setIhBrush-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la tabla de objetos EMF del pincel para rellenar la región. |
| [getRgnData()](#getRgnData--) | Obtiene o establece una matriz de bytes de longitud RgnDataSize que contiene un objeto RegionData (sección 2.2.24). |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Obtiene o establece una matriz de bytes de longitud RgnDataSize que contiene un objeto RegionData (sección 2.2.24). |
### EmfFillRgn(EmfRecord source) {#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillRgn(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfFillRgn`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfFillRgn() {#EmfFillRgn--}
```
public EmfFillRgn()
```


Inicializa una nueva instancia de la clase `EmfFillRgn`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador.

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


Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la tabla de objetos EMF del pincel para rellenar la región.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la tabla de objetos EMF del pincel para rellenar la región.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Obtiene o establece una matriz de bytes de longitud RgnDataSize que contiene un objeto RegionData (sección 2.2.24).

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Obtiene o establece una matriz de bytes de longitud RgnDataSize que contiene un objeto RegionData (sección 2.2.24).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

