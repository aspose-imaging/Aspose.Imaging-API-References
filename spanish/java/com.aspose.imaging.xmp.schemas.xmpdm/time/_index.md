---
title: "Time"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representación de un valor de tiempo en segundos."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.xmp.schemas.xmpdm/time/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Representación de un valor de tiempo en segundos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.imaging.xmp.types.derived.Rational-int-) | Inicializa una nueva instancia de la clase `Time`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getScale()](#getScale--) | Obtiene o establece la escala para el valor de tiempo. |
| [setScale(Rational value)](#setScale-com.aspose.imaging.xmp.types.derived.Rational-) | Obtiene o establece la escala para el valor de tiempo. |
| [getValue()](#getValue--) | Obtiene o establece el valor de tiempo en la escala especificada. |
| [setValue(int value)](#setValue-int-) | Obtiene o establece el valor de tiempo en la escala especificada. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtiene el valor de cadena contenido en formato XMP. |
### Time(Rational scale, int value) {#Time-com.aspose.imaging.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Inicializa una nueva instancia de la clase `Time`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) | La escala. |
| valor | int | El valor. |

### getScale() {#getScale--}
```
public Rational getScale()
```


Obtiene o establece la escala para el valor de tiempo.

Para NTSC, use 1001/30000, o el menos preciso 100/2997. Para PAL, use 1/25. Valor: La escala para el valor de tiempo.

**Returns:**
[Rational](../../com.aspose.imaging.xmp.types.derived/rational)
### setScale(Rational value) {#setScale-com.aspose.imaging.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Obtiene o establece la escala para el valor de tiempo.

Para NTSC, use 1001/30000, o el menos preciso 100/2997. Para PAL, use 1/25. Valor: La escala para el valor de tiempo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) |  |

### getValue() {#getValue--}
```
public int getValue()
```


Obtiene o establece el valor de tiempo en la escala especificada.

Valor: El valor de tiempo en la escala especificada.

**Returns:**
int
### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Obtiene o establece el valor de tiempo en la escala especificada.

Valor: El valor de tiempo en la escala especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Obtiene el valor de cadena contenido en formato XMP.

**Returns:**
java.lang.String - Devuelve el valor de cadena contenido en formato XMP.
