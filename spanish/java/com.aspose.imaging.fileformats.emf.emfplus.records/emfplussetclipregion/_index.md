---
title: "EmfPlusSetClipRegion"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusSetClipRegion combina la región de recorte actual con otra región gráfica."
type: docs
weight: 57
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRegion extends EmfPlusClippingRecordType
```

El registro EmfPlusSetClipRegion combina la región de recorte actual con otra región gráfica. La nueva región de recorte actual se establece al resultado de realizar la operación CombineMode sobre la región de recorte actual anterior y el objeto EmfPlusRegion especificado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusSetClipRegion(EmfPlusRecord source)](#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusSetClipRegion`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCm()](#getCm--) | Obtiene o establece el CM (4 bits): Especifica la operación lógica para combinar dos regiones. |
| [setCm(byte value)](#setCm-byte-) | Obtiene o establece el CM (4 bits): Especifica la operación lógica para combinar dos regiones. |
| [getObjectId()](#getObjectId--) | Obtiene o establece el índice de un objeto EmfPlusRegion (sección 2.2.1.8) en la tabla de objetos EMF+. El valor DEBE estar entre 0 y 63, inclusive. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el índice de un objeto EmfPlusRegion (sección 2.2.1.8) en la tabla de objetos EMF+. El valor DEBE estar entre 0 y 63, inclusive. |
### EmfPlusSetClipRegion(EmfPlusRecord source) {#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRegion(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusSetClipRegion`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getCm() {#getCm--}
```
public byte getCm()
```


Obtiene o establece el CM (4 bits): Especifica la operación lógica para combinar dos regiones. Consulte la enumeración CombineMode (sección 2.1.1.4) para conocer el significado de los valores.

Valor: El cm.

**Returns:**
byte
### setCm(byte value) {#setCm-byte-}
```
public void setCm(byte value)
```


Obtiene o establece el CM (4 bits): Especifica la operación lógica para combinar dos regiones. Consulte la enumeración CombineMode (sección 2.1.1.4) para conocer el significado de los valores.

Valor: El cm.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene o establece el índice de un objeto EmfPlusRegion (sección 2.2.1.8) en la tabla de objetos EMF+. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el índice de un objeto EmfPlusRegion (sección 2.2.1.8) en la tabla de objetos EMF+. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

