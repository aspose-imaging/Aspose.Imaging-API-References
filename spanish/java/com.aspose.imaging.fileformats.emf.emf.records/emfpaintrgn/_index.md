---
title: "EmfPaintRgn"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_PAINTRGN pinta la región especificada utilizando el pincel actualmente seleccionado en el contexto del dispositivo de reproducción."
type: docs
weight: 80
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPaintRgn extends EmfDrawingRecordType
```

El registro EMR\_PAINTRGN pinta la región especificada usando el pincel actualmente seleccionado en el contexto del dispositivo de reproducción.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPaintRgn(EmfRecord source)](#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfPaintRgn`. |
| [EmfPaintRgn()](#EmfPaintRgn--) | Inicializa una nueva instancia de la clase `EmfPaintRgn`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador. |
| [getRgnDataSize()](#getRgnDataSize--) | Obtiene un entero sin signo de 32 bits que especifica el tamaño de los datos de la región, en bytes. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región, en bytes. |
| [getRgnData()](#getRgnData--) | Obtiene una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData (sección 2.2.24), en unidades lógicas. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData (sección 2.2.24), en unidades lógicas. |
### EmfPaintRgn(EmfRecord source) {#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPaintRgn(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfPaintRgn`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfPaintRgn() {#EmfPaintRgn--}
```
public EmfPaintRgn()
```


Inicializa una nueva instancia de la clase `EmfPaintRgn`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Obtiene un entero sin signo de 32 bits que especifica el tamaño de los datos de la región, en bytes.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región, en bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Obtiene una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData (sección 2.2.24), en unidades lógicas.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData (sección 2.2.24), en unidades lógicas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

