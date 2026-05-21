---
title: "EmfText"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmrText contiene valores para la salida de texto."
type: docs
weight: 35
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emftext/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfText extends EmfObject
```

El objeto EmrText contiene valores para la salida de texto.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfText()](#EmfText--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getReference()](#getReference--) | Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica las coordenadas del punto de referencia utilizado para posicionar la cadena. |
| [setReference(Point value)](#setReference-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica las coordenadas del punto de referencia utilizado para posicionar la cadena. |
| [getChars()](#getChars--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres en la cadena |
| [setChars(int value)](#setChars-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres en la cadena |
| [getOptions()](#getOptions--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo usar el rectángulo especificado en el campo Rectangle. |
| [setOptions(int value)](#setOptions-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo usar el rectángulo especificado en el campo Rectangle. |
| [getRectangle()](#getRectangle--) | Obtiene o establece un objeto WMF RectL opcional ([MS-WMF] sección 2.2.2.19) que define un rectángulo de recorte y/o opacidad en unidades lógicas. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL opcional ([MS-WMF] sección 2.2.2.19) que define un rectángulo de recorte y/o opacidad en unidades lógicas. |
| [getStringBuffer()](#getStringBuffer--) | Obtiene o establece el búfer de cadena de caracteres UndefinedSpace1 (variable): Un número opcional de bytes no utilizados. |
| [setStringBuffer(String value)](#setStringBuffer-java.lang.String-) | Obtiene o establece el búfer de cadena de caracteres UndefinedSpace1 (variable): Un número opcional de bytes no utilizados. |
| [getGlyphIndexBuffer()](#getGlyphIndexBuffer--) | Obtiene el búfer opcional de índices de glifos. |
| [setGlyphIndexBuffer(int[] value)](#setGlyphIndexBuffer-int---) | Establece el búfer opcional de índices de glifos. |
| [getDxBuffer()](#getDxBuffer--) | Obtiene o establece el búfer opcional de espaciado de caracteres UndefinedSpace2 (variable): Un número opcional de bytes no utilizados. |
| [setDxBuffer(int[] value)](#setDxBuffer-int---) | Obtiene o establece el búfer opcional de espaciado de caracteres UndefinedSpace2 (variable): Un número opcional de bytes no utilizados. |
### EmfText() {#EmfText--}
```
public EmfText()
```


### getReference() {#getReference--}
```
public Point getReference()
```


Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica las coordenadas del punto de referencia utilizado para posicionar la cadena. El punto de referencia se define mediante el último registro EMR\_SETTEXTALIGN (sección 2.3.11.25). Si no se ha establecido dicho registro, la alineación predeterminada es TA\_LEFT,TA\_TOP.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setReference(Point value) {#setReference-com.aspose.imaging.Point-}
```
public void setReference(Point value)
```


Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica las coordenadas del punto de referencia utilizado para posicionar la cadena. El punto de referencia se define mediante el último registro EMR\_SETTEXTALIGN (sección 2.3.11.25). Si no se ha establecido dicho registro, la alineación predeterminada es TA\_LEFT,TA\_TOP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getChars() {#getChars--}
```
public int getChars()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres en la cadena

**Returns:**
int
### setChars(int value) {#setChars-int-}
```
public void setChars(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres en la cadena

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getOptions() {#getOptions--}
```
public int getOptions()
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo usar el rectángulo especificado en el campo Rectangle. Este campo puede ser una combinación de más de un valor de la enumeración ExtTextOutOptions (sección 2.1.11).

**Returns:**
int
### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo usar el rectángulo especificado en el campo Rectangle. Este campo puede ser una combinación de más de un valor de la enumeración ExtTextOutOptions (sección 2.1.11).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Obtiene o establece un objeto WMF RectL opcional ([MS-WMF] sección 2.2.2.19) que define un rectángulo de recorte y/o opacidad en unidades lógicas. Este rectángulo se aplica a la salida de texto realizada por el registro contenedor.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Obtiene o establece un objeto WMF RectL opcional ([MS-WMF] sección 2.2.2.19) que define un rectángulo de recorte y/o opacidad en unidades lógicas. Este rectángulo se aplica a la salida de texto realizada por el registro contenedor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStringBuffer() {#getStringBuffer--}
```
public String getStringBuffer()
```


Obtiene o establece el búfer de cadena de caracteres UndefinedSpace1 (variable): Un número opcional de bytes no utilizados. No se requiere que el campo OutputString siga inmediatamente a la porción anterior de esta estructura. OutputString (variable): Una matriz de caracteres que especifica la cadena a emitir. La ubicación de este campo se especifica mediante el valor de offString en bytes desde el inicio de este registro. El número de caracteres se especifica mediante el valor de Chars.

**Returns:**
java.lang.String
### setStringBuffer(String value) {#setStringBuffer-java.lang.String-}
```
public void setStringBuffer(String value)
```


Obtiene o establece el búfer de cadena de caracteres UndefinedSpace1 (variable): Un número opcional de bytes no utilizados. No se requiere que el campo OutputString siga inmediatamente a la porción anterior de esta estructura. OutputString (variable): Una matriz de caracteres que especifica la cadena a emitir. La ubicación de este campo se especifica mediante el valor de offString en bytes desde el inicio de este registro. El número de caracteres se especifica mediante el valor de Chars.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGlyphIndexBuffer() {#getGlyphIndexBuffer--}
```
public int[] getGlyphIndexBuffer()
```


Obtiene el búfer opcional de índices de glifos. Si las opciones tienen la bandera ETO\_GLYPH\_INDEX, entonces los códigos de los caracteres en una cadena de texto de salida son en realidad índices de los glifos de caracteres en una fuente TrueType (enumeración ExtTextOutOptions 2.1.11). Los índices de glifos son específicos de la fuente, por lo que para mostrar los caracteres correctos durante la reproducción, la fuente que se use DEBE ser idéntica a la fuente utilizada para generar los índices.

**Returns:**
int[] - el búfer opcional de índices de glifos.
### setGlyphIndexBuffer(int[] value) {#setGlyphIndexBuffer-int---}
```
public void setGlyphIndexBuffer(int[] value)
```


Establece el búfer opcional de índices de glifos. Si las opciones tienen la bandera ETO\_GLYPH\_INDEX, entonces los códigos de los caracteres en una cadena de texto de salida son en realidad índices de los glifos de caracteres en una fuente TrueType (enumeración ExtTextOutOptions 2.1.11). Los índices de glifos son específicos de la fuente, por lo que para mostrar los caracteres correctos durante la reproducción, la fuente que se use DEBE ser idéntica a la fuente utilizada para generar los índices.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | el búfer opcional de índices de glifos. |

### getDxBuffer() {#getDxBuffer--}
```
public int[] getDxBuffer()
```


Obtiene o establece el búfer opcional de espaciado de caracteres UndefinedSpace2 (variable): Un número opcional de bytes no utilizados. No se requiere que el campo OutputDx siga inmediatamente a la porción anterior de esta estructura. OutputDx (variable): Una matriz de enteros sin signo de 32 bits que especifica el espaciado de salida entre los orígenes de celdas de caracteres adyacentes en unidades lógicas. La ubicación de este campo se especifica mediante el valor de offDx en bytes desde el inicio de este registro. Si el espaciado está definido, este campo contiene la misma cantidad de valores que caracteres en la cadena de salida. Si el campo Options del objeto EmrText contiene la bandera ETO\_PDY, entonces este búfer contiene el doble de valores que caracteres hay en la cadena de salida, un desplazamiento horizontal y uno vertical para cada uno, en ese orden. Si se especifica ETO\_RTLREADING, los caracteres se disponen de derecha a izquierda en lugar de izquierda a derecha. Ninguna otra opción afecta la interpretación de este campo.

**Returns:**
int[]
### setDxBuffer(int[] value) {#setDxBuffer-int---}
```
public void setDxBuffer(int[] value)
```


Obtiene o establece el búfer opcional de espaciado de caracteres UndefinedSpace2 (variable): Un número opcional de bytes no utilizados. No se requiere que el campo OutputDx siga inmediatamente a la porción anterior de esta estructura. OutputDx (variable): Una matriz de enteros sin signo de 32 bits que especifica el espaciado de salida entre los orígenes de celdas de caracteres adyacentes en unidades lógicas. La ubicación de este campo se especifica mediante el valor de offDx en bytes desde el inicio de este registro. Si el espaciado está definido, este campo contiene la misma cantidad de valores que caracteres en la cadena de salida. Si el campo Options del objeto EmrText contiene la bandera ETO\_PDY, entonces este búfer contiene el doble de valores que caracteres hay en la cadena de salida, un desplazamiento horizontal y uno vertical para cada uno, en ese orden. Si se especifica ETO\_RTLREADING, los caracteres se disponen de derecha a izquierda en lugar de izquierda a derecha. Ninguna otra opción afecta la interpretación de este campo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

