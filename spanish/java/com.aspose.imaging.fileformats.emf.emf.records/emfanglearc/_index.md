---
title: "EmfAngleArc"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_ANGLEARC especifica un segmento de línea de un arco."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfAngleArc extends EmfDrawingRecordType
```

El registro EMR\_ANGLEARC especifica un segmento de línea de un arco. El segmento de línea se dibuja desde la posición actual hasta el inicio del arco. El arco se dibuja a lo largo del perímetro de un círculo con el radio y centro dados. La longitud del arco está definida por los ángulos de inicio y barrido proporcionados.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfAngleArc(EmfRecord source)](#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfAngleArc`. |
| [EmfAngleArc()](#EmfAngleArc--) | Inicializa una nueva instancia de la clase `EmfAngleArc`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCenter()](#getCenter--) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que indica las coordenadas lógicas del centro del círculo. |
| [setCenter(Point value)](#setCenter-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que indica las coordenadas lógicas del centro del círculo. |
| [getRadius()](#getRadius--) | Obtiene o establece un entero sin signo de 32 bits que especifica el radio del círculo, en unidades lógicas. |
| [setRadius(int value)](#setRadius-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el radio del círculo, en unidades lógicas. |
| [getStartAngle()](#getStartAngle--) | Obtiene o establece un número de punto flotante de 32 bits que especifica el ángulo inicial del arco, en grados. |
| [setStartAngle(float value)](#setStartAngle-float-) | Obtiene o establece un número de punto flotante de 32 bits que especifica el ángulo inicial del arco, en grados. |
| [getSweepAngle()](#getSweepAngle--) | Obtiene o establece un número de punto flotante de 32 bits que especifica el ángulo de barrido del arco, en grados. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Obtiene o establece un número de punto flotante de 32 bits que especifica el ángulo de barrido del arco, en grados. |
### EmfAngleArc(EmfRecord source) {#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAngleArc(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfAngleArc`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfAngleArc() {#EmfAngleArc--}
```
public EmfAngleArc()
```


Inicializa una nueva instancia de la clase `EmfAngleArc`.

### getCenter() {#getCenter--}
```
public Point getCenter()
```


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que indica las coordenadas lógicas del centro del círculo.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setCenter(Point value) {#setCenter-com.aspose.imaging.Point-}
```
public void setCenter(Point value)
```


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que indica las coordenadas lógicas del centro del círculo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getRadius() {#getRadius--}
```
public int getRadius()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el radio del círculo, en unidades lógicas.

**Returns:**
int
### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el radio del círculo, en unidades lógicas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Obtiene o establece un número de punto flotante de 32 bits que especifica el ángulo inicial del arco, en grados.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Obtiene o establece un número de punto flotante de 32 bits que especifica el ángulo inicial del arco, en grados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Obtiene o establece un número de punto flotante de 32 bits que especifica el ángulo de barrido del arco, en grados.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Obtiene o establece un número de punto flotante de 32 bits que especifica el ángulo de barrido del arco, en grados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

