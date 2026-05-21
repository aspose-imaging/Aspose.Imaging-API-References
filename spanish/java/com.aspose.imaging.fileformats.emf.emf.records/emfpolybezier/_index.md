---
title: "EmfPolyBezier"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_POLYBEZIER especifica una o más curvas de Bézier."
type: docs
weight: 85
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezier extends EmfPolyShape
```

El registro EMR\_POLYBEZIER especifica una o más curvas de Bézier.

Las curvas Bézier cúbicas se definen usando los puntos finales y los puntos de control especificados por el campo aPoints. La primera curva se dibuja desde el primer punto hasta el cuarto punto, usando el segundo y tercer punto como puntos de control. Cada curva subsiguiente en la secuencia necesita exactamente tres puntos más: el punto final de la curva anterior se usa como punto de inicio, los dos siguientes puntos de la secuencia son puntos de control, y el tercero es el punto final. Las curvas Bézier cúbicas DEBERÍAN dibujarse usando la pluma actual.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPolyBezier(EmfRecord source)](#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfPolyBezier`. |
| [EmfPolyBezier()](#EmfPolyBezier--) | Inicializa una nueva instancia de la clase `EmfPolyBezier`. |
### EmfPolyBezier(EmfRecord source) {#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezier(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfPolyBezier`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfPolyBezier() {#EmfPolyBezier--}
```
public EmfPolyBezier()
```


Inicializa una nueva instancia de la clase `EmfPolyBezier`.

