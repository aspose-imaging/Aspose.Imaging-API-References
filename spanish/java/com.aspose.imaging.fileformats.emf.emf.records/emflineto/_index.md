---
title: "EmfLineTo"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_LINETO especifica una línea desde la posición actual hasta, pero sin incluir, el punto especificado. Restablece la posición actual al punto especificado."
type: docs
weight: 68
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emflineto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfLineTo extends EmfRecord
```

El registro EMR\_LINETO especifica una línea desde la posición actual hasta, pero sin incluir, el punto especificado. Restablece la posición actual al punto especificado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfLineTo(EmfRecord record)](#EmfLineTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfLineTo`. |
| [EmfLineTo()](#EmfLineTo--) | Inicializa una nueva instancia de la clase `EmfLineTo`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPoint()](#getPoint--) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en [MS-WMF] sección 2.2.2.15, que indica las coordenadas del punto final de la línea. |
| [setPoint(Point value)](#setPoint-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en [MS-WMF] sección 2.2.2.15, que indica las coordenadas del punto final de la línea. |
### EmfLineTo(EmfRecord record) {#EmfLineTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfLineTo(EmfRecord record)
```


Inicializa una nueva instancia de la clase `EmfLineTo`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El registro. |

### EmfLineTo() {#EmfLineTo--}
```
public EmfLineTo()
```


Inicializa una nueva instancia de la clase `EmfLineTo`.

### getPoint() {#getPoint--}
```
public Point getPoint()
```


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en [MS-WMF] sección 2.2.2.15, que indica las coordenadas del punto final de la línea.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setPoint(Point value) {#setPoint-com.aspose.imaging.Point-}
```
public void setPoint(Point value)
```


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en [MS-WMF] sección 2.2.2.15, que indica las coordenadas del punto final de la línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

