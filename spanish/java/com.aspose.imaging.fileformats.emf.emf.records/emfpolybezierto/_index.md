---
title: "EmfPolyBezierTo"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_POLYBEZIERTO especifica una o más curvas Bézier basadas en la posición actual."
type: docs
weight: 87
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezierto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezierTo extends EmfPolyShape
```

El registro EMR\_POLYBEZIERTO especifica una o más curvas de Bézier basadas en la posición actual.

Las curvas Bézier cúbicas se definen usando los puntos finales y los puntos de control especificados por el campo aPoints. La primera curva se dibuja desde el primer punto hasta el cuarto punto, usando el segundo y tercer punto como puntos de control. Cada curva subsiguiente en la secuencia necesita exactamente tres puntos más: el punto final de la curva anterior se usa como punto de inicio, los dos siguientes puntos de la secuencia son puntos de control, y el tercero es el punto final. Las curvas Bézier cúbicas DEBERÍAN dibujarse usando la pluma actual.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPolyBezierTo(EmfRecord source)](#EmfPolyBezierTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfPolyBezierTo`. |
| [EmfPolyBezierTo()](#EmfPolyBezierTo--) | Inicializa una nueva instancia de la clase `EmfPolyBezierTo`. |
### EmfPolyBezierTo(EmfRecord source) {#EmfPolyBezierTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezierTo(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfPolyBezierTo`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfPolyBezierTo() {#EmfPolyBezierTo--}
```
public EmfPolyBezierTo()
```


Inicializa una nueva instancia de la clase `EmfPolyBezierTo`.

