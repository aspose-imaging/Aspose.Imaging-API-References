---
title: "EmfPlusDrawString"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusDrawString especifica la salida de texto con formato de cadena."
type: docs
weight: 28
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawString extends EmfPlusDrawingRecordType
```

El registro EmfPlusDrawString especifica la salida de texto con formato de cadena.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusDrawString(EmfPlusRecord source)](#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusDrawString`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isColor()](#isColor--) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [setColor(boolean value)](#setColor-boolean-) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [getObjectId()](#getObjectId--) | Obtiene o establece el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el identificador del objeto. |
| [getBrushId()](#getBrushId--) | Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que especifica el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que especifica el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
| [getFormatId()](#getFormatId--) | Obtiene o establece el identificador de formato, un entero sin signo de 32 bits que especifica el índice de un objeto opcional EmfPlusStringFormat (sección 2.2.1.9) en la tabla de objetos EMF+. |
| [setFormatId(int value)](#setFormatId-int-) | Obtiene o establece el identificador de formato, un entero sin signo de 32 bits que especifica el índice de un objeto opcional EmfPlusStringFormat (sección 2.2.1.9) en la tabla de objetos EMF+. |
| [getLength()](#getLength--) | Obtiene o establece la longitud, un entero sin signo de 32 bits que especifica el número de caracteres en la cadena. |
| [setLength(int value)](#setLength-int-) | Obtiene o establece la longitud, un entero sin signo de 32 bits que especifica el número de caracteres en la cadena. |
| [getLayoutRect()](#getLayoutRect--) | Obtiene o establece el rectángulo de diseño, un objeto EmfPlusRectF (sección 2.2.2.39) que define el área delimitada del destino que recibirá la cadena. |
| [setLayoutRect(RectangleF value)](#setLayoutRect-com.aspose.imaging.RectangleF-) | Obtiene o establece el rectángulo de diseño, un objeto EmfPlusRectF (sección 2.2.2.39) que define el área delimitada del destino que recibirá la cadena. |
| [getStringData()](#getStringData--) | Obtiene o establece los datos de la cadena, una matriz de caracteres Unicode de 16 bits que especifica la cadena a dibujar. |
| [setStringData(String value)](#setStringData-java.lang.String-) | Obtiene o establece los datos de la cadena, una matriz de caracteres Unicode de 16 bits que especifica la cadena a dibujar. |
### EmfPlusDrawString(EmfPlusRecord source) {#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawString(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusDrawString`.

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusFont (sección 2.2.1.3) en la tabla de objetos EMF+ para renderizar el texto. El valor DEBE estar entre cero y 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusFont (sección 2.2.1.3) en la tabla de objetos EMF+ para renderizar el texto. El valor DEBE estar entre cero y 63, inclusive.

Valor: El identificador del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que especifica el pincel, cuyo contenido está determinado por el bit S en el campo Flags. Esta definición se usa para pintar el color del texto en primer plano; es decir, solo los glifos mismos.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que especifica el pincel, cuyo contenido está determinado por el bit S en el campo Flags. Esta definición se usa para pintar el color del texto en primer plano; es decir, solo los glifos mismos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFormatId() {#getFormatId--}
```
public int getFormatId()
```


Obtiene o establece el identificador de formato, un entero sin signo de 32 bits que especifica el índice de un objeto opcional EmfPlusStringFormat (sección 2.2.1.9) en la tabla de objetos EMF+. Este objeto especifica la información de diseño de texto y las manipulaciones de visualización que se aplicarán a una cadena.

**Returns:**
int
### setFormatId(int value) {#setFormatId-int-}
```
public void setFormatId(int value)
```


Obtiene o establece el identificador de formato, un entero sin signo de 32 bits que especifica el índice de un objeto opcional EmfPlusStringFormat (sección 2.2.1.9) en la tabla de objetos EMF+. Este objeto especifica la información de diseño de texto y las manipulaciones de visualización que se aplicarán a una cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLength() {#getLength--}
```
public int getLength()
```


Obtiene o establece la longitud, un entero sin signo de 32 bits que especifica el número de caracteres en la cadena.

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Obtiene o establece la longitud, un entero sin signo de 32 bits que especifica el número de caracteres en la cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLayoutRect() {#getLayoutRect--}
```
public RectangleF getLayoutRect()
```


Obtiene o establece el rectángulo de diseño, un objeto EmfPlusRectF (sección 2.2.2.39) que define el área delimitada del destino que recibirá la cadena.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setLayoutRect(RectangleF value) {#setLayoutRect-com.aspose.imaging.RectangleF-}
```
public void setLayoutRect(RectangleF value)
```


Obtiene o establece el rectángulo de diseño, un objeto EmfPlusRectF (sección 2.2.2.39) que define el área delimitada del destino que recibirá la cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStringData() {#getStringData--}
```
public String getStringData()
```


Obtiene o establece los datos de la cadena, una matriz de caracteres Unicode de 16 bits que especifica la cadena a dibujar.

**Returns:**
java.lang.String
### setStringData(String value) {#setStringData-java.lang.String-}
```
public void setStringData(String value)
```


Obtiene o establece los datos de la cadena, una matriz de caracteres Unicode de 16 bits que especifica la cadena a dibujar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

