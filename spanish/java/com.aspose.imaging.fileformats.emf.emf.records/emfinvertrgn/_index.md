---
title: "EmfInvertRgn"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_INVERTRGN invierte los colores en la región especificada."
type: docs
weight: 67
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfInvertRgn extends EmfStateRecordType
```

El registro EMR\_INVERTRGN invierte los colores en la región especificada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfInvertRgn(EmfRecord source)](#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfInvertRgn`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que define el rectángulo delimitador. |
| [getRgnDataSize()](#getRgnDataSize--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región, en bytes. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región, en bytes. |
| [getRgnData()](#getRgnData--) | Obtiene o establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData, en unidades lógicas. |
| [setRgnData(byte[] value)](#setRgnData-byte---) | Obtiene o establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData, en unidades lógicas. |
### EmfInvertRgn(EmfRecord source) {#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfInvertRgn(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfInvertRgn`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

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

### getRgnData() {#getRgnData--}
```
public byte[] getRgnData()
```


Obtiene o establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData, en unidades lógicas.

**Returns:**
byte[]
### setRgnData(byte[] value) {#setRgnData-byte---}
```
public void setRgnData(byte[] value)
```


Obtiene o establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData, en unidades lógicas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

