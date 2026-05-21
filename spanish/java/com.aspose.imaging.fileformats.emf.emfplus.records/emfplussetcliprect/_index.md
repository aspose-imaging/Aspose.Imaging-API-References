---
title: "EmfPlusSetClipRect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusSetClipRect combina la región de recorte actual con un rectángulo."
type: docs
weight: 56
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRect extends EmfPlusClippingRecordType
```

El registro EmfPlusSetClipRect combina la región de recorte actual con un rectángulo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusSetClipRect(EmfPlusRecord source)](#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusSetClipRect`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCm()](#getCm--) | Obtiene o establece el CM (4 bits): Especifica la operación lógica para combinar dos regiones. |
| [setCm(byte value)](#setCm-byte-) | Obtiene o establece el CM (4 bits): Especifica la operación lógica para combinar dos regiones. |
| [getClipRect()](#getClipRect--) | Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que define el rectángulo a usar en la operación CombineMode. |
| [setClipRect(RectangleF value)](#setClipRect-com.aspose.imaging.RectangleF-) | Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que define el rectángulo a usar en la operación CombineMode. |
### EmfPlusSetClipRect(EmfPlusRecord source) {#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRect(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusSetClipRect`.

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

### getClipRect() {#getClipRect--}
```
public RectangleF getClipRect()
```


Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que define el rectángulo a usar en la operación CombineMode.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setClipRect(RectangleF value) {#setClipRect-com.aspose.imaging.RectangleF-}
```
public void setClipRect(RectangleF value)
```


Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que define el rectángulo a usar en la operación CombineMode.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

