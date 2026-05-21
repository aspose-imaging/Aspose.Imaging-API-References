---
title: "EmfExtSelectClipRgn"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_EXTSELECTCLIPRGN combina la región especificada con la región de recorte actual usando el modo especificado."
type: docs
weight: 55
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExtSelectClipRgn extends EmfClippingRecordType
```

El registro EMR\_EXTSELECTCLIPRGN combina la región especificada con la región de recorte actual usando el modo especificado. Nota: los campos que no se describen en esta sección se especifican en la sección 2.3.2.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfExtSelectClipRgn(EmfRecord source)](#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfExtSelectClipRgn`. |
| [EmfExtSelectClipRgn()](#EmfExtSelectClipRgn--) | Inicializa una nueva instancia de la clase `EmfExtSelectClipRgn`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRgnDataSize()](#getRgnDataSize--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región en bytes. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región en bytes. |
| [getRegionMode()](#getRegionMode--) | Obtiene o establece un entero sin signo de 32 bits que especifica la forma de usar la región. |
| [setRegionMode(int value)](#setRegionMode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica la forma de usar la región. |
| [getRgnData()](#getRgnData--) | Obtiene o establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData en unidades lógicas. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Obtiene o establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData en unidades lógicas. |
### EmfExtSelectClipRgn(EmfRecord source) {#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtSelectClipRgn(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfExtSelectClipRgn`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfExtSelectClipRgn() {#EmfExtSelectClipRgn--}
```
public EmfExtSelectClipRgn()
```


Inicializa una nueva instancia de la clase `EmfExtSelectClipRgn`.

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región en bytes.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región en bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica la forma de usar la región. El valor DEBE estar en la enumeración RegionMode (sección 2.1.29).

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica la forma de usar la región. El valor DEBE estar en la enumeración RegionMode (sección 2.1.29).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Obtiene o establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData en unidades lógicas. Si RegionMode es RGN\_COPY, estos datos pueden omitirse y la región de recorte DEBERÍA establecerse en la región de recorte predeterminada (NULL).

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Obtiene o establece una matriz de bytes de longitud RgnDataSize que especifica un objeto RegionData en unidades lógicas. Si RegionMode es RGN\_COPY, estos datos pueden omitirse y la región de recorte DEBERÍA establecerse en la región de recorte predeterminada (NULL).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

