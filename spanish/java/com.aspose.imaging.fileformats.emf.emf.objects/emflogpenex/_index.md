---
title: "EmfLogPenEx"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto LogPenEx especifica el ancho de estilo y el color de un lápiz lógico extendido."
type: docs
weight: 28
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPenEx extends EmfBasePen
```

El objeto LogPenEx especifica el estilo, ancho y color de una pluma lógica extendida.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfLogPenEx()](#EmfLogPenEx--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Obtiene o establece el estilo del lápiz. |
| [setPenStyle(int value)](#setPenStyle-int-) | Obtiene o establece el estilo del lápiz. |
| [getWidth()](#getWidth--) | Obtiene o establece un entero sin signo de 32 bits que especifica el ancho de la línea dibujada por el lápiz. |
| [setWidth(int value)](#setWidth-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el ancho de la línea dibujada por el lápiz. |
| [getBrushStyle()](#getBrushStyle--) | Obtiene o establece un entero sin signo de 32 bits que especifica un estilo de pincel para el lápiz a partir de la enumeración WMF BrushStyle ([MS-WMF] sección 2.1.1.4). |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica un estilo de pincel para el lápiz a partir de la enumeración WMF BrushStyle ([MS-WMF] sección 2.1.1.4). |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8). |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8). |
| [getBrushHatch()](#getBrushHatch--) | Obtiene o establece el patrón de trama del pincel. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Obtiene o establece el patrón de trama del pincel. |
| [getNumStyleEntities()](#getNumStyleEntities--) | Obtiene el número de elementos en la matriz especificada en el campo StyleEntry. |
| [getStyleEntry()](#getStyleEntry--) | Obtiene o establece una matriz opcional de enteros sin signo de 32 bits que define las longitudes de guiones y espacios en la línea dibujada por este lápiz, cuando el valor de PenStyle es PS\_USERSTYLE estilo de línea para el lápiz. |
| [setStyleEntry(int[] value)](#setStyleEntry-int---) | Obtiene o establece una matriz opcional de enteros sin signo de 32 bits que define las longitudes de guiones y espacios en la línea dibujada por este lápiz, cuando el valor de PenStyle es PS\_USERSTYLE estilo de línea para el lápiz. |
| [getBrushDibPattern()](#getBrushDibPattern--) | Obtiene o establece el patrón dib del pincel. |
| [setBrushDibPattern(WmfDeviceIndependentBitmap value)](#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtiene o establece el patrón dib del pincel. |
### EmfLogPenEx() {#EmfLogPenEx--}
```
public EmfLogPenEx()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Obtiene o establece el estilo del lápiz.

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Obtiene o establece el estilo del lápiz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el ancho de la línea dibujada por el lápiz. Si el tipo de lápiz en el campo PenStyle es PS\_GEOMETRIC, este valor es el ancho en unidades lógicas; de lo contrario, el ancho se especifica en unidades de dispositivo. Si el tipo de lápiz en el campo PenStyle es PS\_COSMETIC, este valor DEBE ser 0x00000001.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el ancho de la línea dibujada por el lápiz. Si el tipo de lápiz en el campo PenStyle es PS\_GEOMETRIC, este valor es el ancho en unidades lógicas; de lo contrario, el ancho se especifica en unidades de dispositivo. Si el tipo de lápiz en el campo PenStyle es PS\_COSMETIC, este valor DEBE ser 0x00000001.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Obtiene o establece un entero sin signo de 32 bits que especifica un estilo de pincel para el lápiz a partir de la enumeración WMF BrushStyle ([MS-WMF] sección 2.1.1.4). Si el tipo de lápiz en el campo PenStyle es PS\_GEOMETRIC, este valor DEBE ser BS\_SOLID o BS\_HATCHED. El valor de este campo puede ser BS\_NULL, pero solo si el estilo de línea especificado en PenStyle es PS\_NULL. El estilo BS\_NULL DEBERÍA usarse para especificar un pincel que no tiene efecto.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica un estilo de pincel para el lápiz a partir de la enumeración WMF BrushStyle ([MS-WMF] sección 2.1.1.4). Si el tipo de lápiz en el campo PenStyle es PS\_GEOMETRIC, este valor DEBE ser BS\_SOLID o BS\_HATCHED. El valor de este campo puede ser BS\_NULL, pero solo si el estilo de línea especificado en PenStyle es PS\_NULL. El estilo BS\_NULL DEBERÍA usarse para especificar un pincel que no tiene efecto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8). La interpretación de este campo depende del valor BrushStyle, como se muestra en la tabla más adelante en esta sección.

Valor: El color ARGB de 32 bits

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8). La interpretación de este campo depende del valor BrushStyle, como se muestra en la tabla más adelante en esta sección.

Valor: El color ARGB de 32 bits

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Obtiene o establece el patrón de trama del pincel. La definición de este campo depende del valor BrushStyle, como se muestra en la tabla más adelante en esta sección.

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Obtiene o establece el patrón de trama del pincel. La definición de este campo depende del valor BrushStyle, como se muestra en la tabla más adelante en esta sección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getNumStyleEntities() {#getNumStyleEntities--}
```
public int getNumStyleEntities()
```


Obtiene el número de elementos en la matriz especificada en el campo StyleEntry. Este valor DEBERÍA ser cero si PenStyle no especifica PS\_USERSTYLE.

**Returns:**
int
### getStyleEntry() {#getStyleEntry--}
```
public int[] getStyleEntry()
```


Obtiene o establece una matriz opcional de enteros sin signo de 32 bits que define las longitudes de guiones y espacios en la línea dibujada por este lápiz, cuando el valor de PenStyle es PS\_USERSTYLE estilo de línea para el lápiz. La matriz contiene un número de entradas especificado por NumStyleEntries, pero se utiliza como si se repitiera indefinidamente. La primera entrada en la matriz especifica la longitud del primer guión. La segunda entrada especifica la longitud del primer espacio. A partir de ahí, las longitudes de guiones y espacios se alternan. Si el tipo de lápiz en el campo PenStyle es PS\_GEOMETRIC, las longitudes se especifican en unidades lógicas; de lo contrario, se especifican en unidades de dispositivo.

**Returns:**
int[]
### setStyleEntry(int[] value) {#setStyleEntry-int---}
```
public void setStyleEntry(int[] value)
```


Obtiene o establece una matriz opcional de enteros sin signo de 32 bits que define las longitudes de guiones y espacios en la línea dibujada por este lápiz, cuando el valor de PenStyle es PS\_USERSTYLE estilo de línea para el lápiz. La matriz contiene un número de entradas especificado por NumStyleEntries, pero se utiliza como si se repitiera indefinidamente. La primera entrada en la matriz especifica la longitud del primer guión. La segunda entrada especifica la longitud del primer espacio. A partir de ahí, las longitudes de guiones y espacios se alternan. Si el tipo de lápiz en el campo PenStyle es PS\_GEOMETRIC, las longitudes se especifican en unidades lógicas; de lo contrario, se especifican en unidades de dispositivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getBrushDibPattern() {#getBrushDibPattern--}
```
public WmfDeviceIndependentBitmap getBrushDibPattern()
```


Obtiene o establece el patrón dib del pincel.

Valor: El patrón dib del pincel.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBrushDibPattern(WmfDeviceIndependentBitmap value) {#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBrushDibPattern(WmfDeviceIndependentBitmap value)
```


Obtiene o establece el patrón dib del pincel.

Valor: El patrón dib del pincel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

