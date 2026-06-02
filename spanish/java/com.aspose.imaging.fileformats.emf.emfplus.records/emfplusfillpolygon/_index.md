---
title: "EmfPlusFillPolygon"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusFillPolygon especifica el relleno del interior de un polígono."
type: docs
weight: 36
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPolygon extends EmfPlusDrawingRecordType
```

El registro EmfPlusFillPolygon especifica el relleno del interior de un polígono.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusFillPolygon(EmfPlusRecord source)](#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusFillPolygon`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isColor()](#isColor--) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [setColor(boolean value)](#setColor-boolean-) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [isCompressed()](#isCompressed--) | Obtiene o establece un valor que indica si esta instancia está comprimida. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si esta instancia está comprimida. |
| [isRelative()](#isRelative--) | Obtiene o establece un valor que indica si esta instancia es relativa. |
| [setRelative(boolean value)](#setRelative-boolean-) | Obtiene o establece un valor que indica si esta instancia es relativa. |
| [getBrushId()](#getBrushId--) | Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
| [getPointData()](#getPointData--) | Obtiene o establece los datos de puntos, una matriz de Count puntos que definen los vértices del polígono. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Obtiene o establece los datos de puntos, una matriz de Count puntos que definen los vértices del polígono. |
### EmfPlusFillPolygon(EmfPlusRecord source) {#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPolygon(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusFillPolygon`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Obtiene o establece un valor que indica si esta instancia es de color. Si está establecido, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1). Si está borrado, BrushId contiene el índice de un objeto EmfPlusBrush (sección 2.2.1.1) en la tabla de objetos EMF+.

Valor: `true` si esta instancia es de color; de lo contrario, `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Obtiene o establece un valor que indica si esta instancia es de color. Si está establecido, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1). Si está borrado, BrushId contiene el índice de un objeto EmfPlusBrush (sección 2.2.1.1) en la tabla de objetos EMF+.

Valor: `true` si esta instancia es de color; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


Obtiene o establece un valor que indica si esta instancia está comprimida. Si está establecida, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. Si no está establecida, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits.

Valor: `true` si esta instancia está comprimida; de lo contrario, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtiene o establece un valor que indica si esta instancia está comprimida. Si está establecida, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. Si no está establecida, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits.

Valor: `true` si esta instancia está comprimida; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### isRelative() {#isRelative--}
```
public boolean isRelative()
```


Obtiene o establece un valor que indica si esta instancia es relativa. Si está establecida, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si no está establecida, PointData especifica ubicaciones absolutas según la bandera C.

Valor: `true` si esta instancia es relativa; de lo contrario, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Obtiene o establece un valor que indica si esta instancia es relativa. Si está establecida, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si no está establecida, PointData especifica ubicaciones absolutas según la bandera C.

Valor: `true` si esta instancia es relativa; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Obtiene o establece los datos del punto. Una matriz de Count puntos que definen los vértices del polígono. Los dos primeros puntos de la matriz especifican el primer lado del polígono. Cada punto adicional especifica un nuevo lado, cuyos vértices incluyen el punto y el punto anterior. Si el último punto y el primer punto no coinciden, especifican el último lado del polígono.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Obtiene o establece los datos del punto. Una matriz de Count puntos que definen los vértices del polígono. Los dos primeros puntos de la matriz especifican el primer lado del polígono. Cada punto adicional especifica un nuevo lado, cuyos vértices incluyen el punto y el punto anterior. Si el último punto y el primer punto no coinciden, especifican el último lado del polígono.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

