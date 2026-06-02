---
title: "EmfPlusDrawImagePoints"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusDrawImagePoints especifica dibujar una imagen escalada dentro de un paralelogramo."
type: docs
weight: 23
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImagePoints extends EmfPlusDrawingRecordType
```

El registro EmfPlusDrawImagePoints especifica dibujar una imagen escalada dentro de un paralelogramo.

Un EmfPlusImage puede especificar ya sea un bitmap o un metafile. Los colores de una imagen pueden manipularse durante el renderizado. Pueden corregirse, oscurecerse, aclararse y eliminarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusDrawImagePoints(EmfPlusRecord source)](#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusDrawImagePoints`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [getObjectId()](#getObjectId--) | Obtiene o establece el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el identificador del objeto. |
| [getApplyingAnEffect()](#getApplyingAnEffect--) | Obtiene o establece un valor que indica si [applying an effect]. |
| [setApplyingAnEffect(boolean value)](#setApplyingAnEffect-boolean-) | Obtiene o establece un valor que indica si [applying an effect]. |
| [getRelative()](#getRelative--) | Obtiene o establece un valor que indica si este `EmfPlusDrawImagePoints` es relativo. |
| [setRelative(boolean value)](#setRelative-boolean-) | Obtiene o establece un valor que indica si este `EmfPlusDrawImagePoints` es relativo. |
| [getImageAttributesId()](#getImageAttributesId--) | Obtiene o establece un entero sin signo de 32 bits que contiene el índice del objeto opcional EmfPlusImageAttributes (sección 2.2.1.5) en la tabla de objetos EMF+. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Obtiene o establece un entero sin signo de 32 bits que contiene el índice del objeto opcional EmfPlusImageAttributes (sección 2.2.1.5) en la tabla de objetos EMF+. |
| [getSrcUnit()](#getSrcUnit--) | Obtiene o establece un entero con signo de 32 bits que define las unidades del campo SrcRect. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Obtiene o establece un entero con signo de 32 bits que define las unidades del campo SrcRect. |
| [getSrcRect()](#getSrcRect--) | Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que define una porción de la imagen a renderizar. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que define una porción de la imagen a renderizar. |
| [getPointData()](#getPointData--) | Obtiene o establece una matriz de puntos Count que especifican tres puntos de un paralelogramo. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Obtiene o establece una matriz de puntos Count que especifican tres puntos de un paralelogramo. |
### EmfPlusDrawImagePoints(EmfPlusRecord source) {#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImagePoints(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusDrawImagePoints`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtiene o establece un valor que indica si los datos de PointData están comprimidos. Este bit indica si el campo PointData especifica datos comprimidos. Si está activado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. Si está desactivado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits. Nota: Si el indicador P (abajo) está activado, este indicador está indefinido y DEBE ser ignorado.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtiene o establece un valor que indica si los datos de PointData están comprimidos. Este bit indica si el campo PointData especifica datos comprimidos. Si está activado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. Si está desactivado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits. Nota: Si el indicador P (abajo) está activado, este indicador está indefinido y DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusImage (sección 2.2.1.4) en la tabla de objetos EMF+, que especifica la imagen a renderizar. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusImage (sección 2.2.1.4) en la tabla de objetos EMF+, que especifica la imagen a renderizar. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getApplyingAnEffect() {#getApplyingAnEffect--}
```
public boolean getApplyingAnEffect()
```


Obtiene o establece un valor que indica si [applying an effect]. Este bit indica que la representación de la imagen incluye la aplicación de un efecto. Si está establecido, un objeto de la clase Effect DEBE haber sido especificado en un registro EmfPlusSerializableObject anterior (sección 2.3.5.2).

Valor: `true` si [applying an effect]; de lo contrario, `false`.

**Returns:**
boolean
### setApplyingAnEffect(boolean value) {#setApplyingAnEffect-boolean-}
```
public void setApplyingAnEffect(boolean value)
```


Obtiene o establece un valor que indica si [applying an effect]. Este bit indica que la representación de la imagen incluye la aplicación de un efecto. Si está establecido, un objeto de la clase Effect DEBE haber sido especificado en un registro EmfPlusSerializableObject anterior (sección 2.3.5.2).

Valor: `true` si [applying an effect]; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Obtiene o establece un valor que indica si este `EmfPlusDrawImagePoints` es relativo. Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas. Si está establecido, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si está desactivado, PointData especifica ubicaciones absolutas según la bandera C. Nota: Si esta bandera está establecida, la bandera C (arriba) es indefinida y DEBE ser ignorada.

Valor: `true` si es relativo; de lo contrario, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Obtiene o establece un valor que indica si este `EmfPlusDrawImagePoints` es relativo. Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas. Si está establecido, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si está desactivado, PointData especifica ubicaciones absolutas según la bandera C. Nota: Si esta bandera está establecida, la bandera C (arriba) es indefinida y DEBE ser ignorada.

Valor: `true` si es relativo; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Obtiene o establece un entero sin signo de 32 bits que contiene el índice del objeto opcional EmfPlusImageAttributes (sección 2.2.1.5) en la tabla de objetos EMF+.

Valor: el identificador de atributos de la imagen.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Obtiene o establece un entero sin signo de 32 bits que contiene el índice del objeto opcional EmfPlusImageAttributes (sección 2.2.1.5) en la tabla de objetos EMF+.

Valor: el identificador de atributos de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Obtiene o establece un entero con signo de 32 bits que define las unidades del campo SrcRect. DEBE ser el valor UnitPixel de la enumeración UnitType (sección 2.1.1.33).

Valor: la unidad de origen.

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Obtiene o establece un entero con signo de 32 bits que define las unidades del campo SrcRect. DEBE ser el valor UnitPixel de la enumeración UnitType (sección 2.1.1.33).

Valor: la unidad de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que define una porción de la imagen a renderizar.

Valor: el rectángulo de origen.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que define una porción de la imagen a renderizar.

Valor: el rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Obtiene o establece una matriz de Count puntos que especifican tres puntos de un paralelogramo. Los tres puntos representan las esquinas superior izquierda, superior derecha e inferior izquierda del paralelogramo. El cuarto punto del paralelogramo se extrapola a partir de los tres primeros. La porción de la imagen especificada por el campo SrcRect DEBERÍA tener transformaciones de escalado y cizallado aplicadas si es necesario para encajar dentro del paralelogramo.

Valor: los datos del punto.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Obtiene o establece una matriz de Count puntos que especifican tres puntos de un paralelogramo. Los tres puntos representan las esquinas superior izquierda, superior derecha e inferior izquierda del paralelogramo. El cuarto punto del paralelogramo se extrapola a partir de los tres primeros. La porción de la imagen especificada por el campo SrcRect DEBERÍA tener transformaciones de escalado y cizallado aplicadas si es necesario para encajar dentro del paralelogramo.

Valor: los datos del punto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

