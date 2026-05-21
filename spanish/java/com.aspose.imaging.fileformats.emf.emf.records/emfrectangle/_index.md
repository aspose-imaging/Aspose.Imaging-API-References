---
title: "EmfRectangle"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_RECTANGLE dibuja un rectángulo."
type: docs
weight: 107
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRectangle extends EmfDrawingRecordType
```

El registro EMR\_RECTANGLE dibuja un rectángulo. El rectángulo se delimita usando la pluma actual y se rellena usando el pincel actual.

La posición actual no se usa ni se actualiza con Rectangle. Si se usa una pluma PS\_NULL, las dimensiones del rectángulo son 1 píxel menos en altura y 1 píxel menos en anchura.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfRectangle(EmfRecord source)](#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfRectangle`. |
| [EmfRectangle()](#EmfRectangle--) | Inicializa una nueva instancia de la clase `EmfRectangle`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBox()](#getBox--) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo inclusivo‑inclusivo a dibujar. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo inclusivo‑inclusivo a dibujar. |
### EmfRectangle(EmfRecord source) {#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRectangle(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfRectangle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfRectangle() {#EmfRectangle--}
```
public EmfRectangle()
```


Inicializa una nueva instancia de la clase `EmfRectangle`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo inclusivo‑inclusivo a dibujar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo inclusivo‑inclusivo a dibujar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

