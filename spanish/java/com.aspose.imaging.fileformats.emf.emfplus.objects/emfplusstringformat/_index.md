---
title: "EmfPlusStringFormat"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusStringFormat especifica manipulaciones de visualización del diseño de texto e identificación de idioma"
type: docs
weight: 74
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusStringFormat extends EmfPlusGraphicsObjectType
```

El objeto EmfPlusStringFormat especifica la disposición del texto, manipulaciones de visualización y la identificación del idioma.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDigitLanguage()](#getDigitLanguage--) | Obtiene o establece un objeto EmfPlusLanguageIdentifier que especifica el idioma a usar para los dígitos numéricos en la cadena. |
| [setDigitLanguage(short value)](#setDigitLanguage-short-) | Obtiene o establece un objeto EmfPlusLanguageIdentifier que especifica el idioma a usar para los dígitos numéricos en la cadena. |
| [getDigitSubstitution()](#getDigitSubstitution--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo sustituir los dígitos numéricos en la cadena según una configuración regional o idioma. |
| [setDigitSubstitution(int value)](#setDigitSubstitution-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo sustituir los dígitos numéricos en la cadena según una configuración regional o idioma. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el número de espacios entre el comienzo de una línea de texto y la primera tabulación. |
| [setFirstTabOffset(float value)](#setFirstTabOffset-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el número de espacios entre el comienzo de una línea de texto y la primera tabulación. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Obtiene o establece un entero con signo de 32 bits que especifica el tipo de procesamiento que se realiza en una cadena cuando se encuentra un prefijo de atajo de teclado (es decir, una ampersand). |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el tipo de procesamiento que se realiza en una cadena cuando se encuentra un prefijo de atajo de teclado (es decir, una ampersand). |
| [getLanguage()](#getLanguage--) | Obtiene o establece un objeto EmfPlusLanguageIdentifier (sección 2.2.2.23) que especifica el idioma a usar para la cadena. |
| [setLanguage(short value)](#setLanguage-short-) | Obtiene o establece un objeto EmfPlusLanguageIdentifier (sección 2.2.2.23) que especifica el idioma a usar para la cadena. |
| [getLeadingMargin()](#getLeadingMargin--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la longitud del espacio a agregar a la posición inicial de una cadena. |
| [setLeadingMargin(float value)](#setLeadingMargin-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la longitud del espacio a agregar a la posición inicial de una cadena. |
| [getLineAlign()](#getLineAlign--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo alinear la cadena verticalmente en el rectángulo de diseño. |
| [setLineAlign(int value)](#setLineAlign-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo alinear la cadena verticalmente en el rectángulo de diseño. |
| [getRangeCount()](#getRangeCount--) | Obtiene o establece un entero con signo de 32 bits que especifica el número de objetos EmfPlusCharacterRange (sección 2.2.2.8) definidos en el campo StringFormatData. |
| [setRangeCount(int value)](#setRangeCount-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el número de objetos EmfPlusCharacterRange (sección 2.2.2.8) definidos en el campo StringFormatData. |
| [getStringAlignment()](#getStringAlignment--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo alinear la cadena horizontalmente en el rectángulo de diseño. |
| [setStringAlignment(int value)](#setStringAlignment-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo alinear la cadena horizontalmente en el rectángulo de diseño. |
| [getStringFormatData()](#getStringFormatData--) | Obtiene o establece un objeto EmfPlusStringFormatData (sección 2.2.2.44) que especifica datos opcionales de diseño de texto. |
| [setStringFormatData(EmfPlusStringFormatData value)](#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-) | Obtiene o establece un objeto EmfPlusStringFormatData (sección 2.2.2.44) que especifica datos opcionales de diseño de texto. |
| [getStringFormatFlags()](#getStringFormatFlags--) | Obtiene o establece un entero sin signo de 32 bits que especifica opciones de diseño de texto para formateo, recorte y manejo de fuentes. |
| [setStringFormatFlags(long value)](#setStringFormatFlags-long-) | Obtiene o establece un entero sin signo de 32 bits que especifica opciones de diseño de texto para formateo, recorte y manejo de fuentes. |
| [getTabstopCount()](#getTabstopCount--) | Obtiene o establece un entero con signo de 32 bits que especifica el número de tabulaciones definidas en el campo StringFormatData. |
| [setTabstopCount(int value)](#setTabstopCount-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el número de tabulaciones definidas en el campo StringFormatData. |
| [getTracking()](#getTracking--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la proporción del espacio horizontal asignado a cada carácter en una cadena especificada respecto al ancho del carácter definido por la fuente. |
| [setTracking(float value)](#setTracking-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la proporción del espacio horizontal asignado a cada carácter en una cadena especificada respecto al ancho del carácter definido por la fuente. |
| [getTrailingMargin()](#getTrailingMargin--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la longitud del espacio a dejar después de una cadena. |
| [setTrailingMargin(float value)](#setTrailingMargin-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica la longitud del espacio a dejar después de una cadena. |
| [getTrimming()](#getTrimming--) | Obtiene o establece cómo recortar caracteres de una cadena que es demasiado grande para caber en un rectángulo de diseño. |
| [setTrimming(int value)](#setTrimming-int-) | Obtiene o establece cómo recortar caracteres de una cadena que es demasiado grande para caber en un rectángulo de diseño. |
### EmfPlusStringFormat() {#EmfPlusStringFormat--}
```
public EmfPlusStringFormat()
```


### getDigitLanguage() {#getDigitLanguage--}
```
public short getDigitLanguage()
```


Obtiene o establece un objeto EmfPlusLanguageIdentifier que especifica el idioma a usar para los dígitos numéricos en la cadena. Por ejemplo, si esta cadena contiene dígitos árabes, este campo DEBE contener un identificador de idioma que especifique un idioma árabe.

**Returns:**
short
### setDigitLanguage(short value) {#setDigitLanguage-short-}
```
public void setDigitLanguage(short value)
```


Obtiene o establece un objeto EmfPlusLanguageIdentifier que especifica el idioma a usar para los dígitos numéricos en la cadena. Por ejemplo, si esta cadena contiene dígitos árabes, este campo DEBE contener un identificador de idioma que especifique un idioma árabe.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getDigitSubstitution() {#getDigitSubstitution--}
```
public int getDigitSubstitution()
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo sustituir los dígitos numéricos en la cadena según una configuración regional o idioma. Este valor DEBE estar definido en la enumeración StringDigitSubstitution (sección 2.1.1.30).

**Returns:**
int
### setDigitSubstitution(int value) {#setDigitSubstitution-int-}
```
public void setDigitSubstitution(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo sustituir los dígitos numéricos en la cadena según una configuración regional o idioma. Este valor DEBE estar definido en la enumeración StringDigitSubstitution (sección 2.1.1.30).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el número de espacios entre el comienzo de una línea de texto y la primera tabulación.

**Returns:**
float
### setFirstTabOffset(float value) {#setFirstTabOffset-float-}
```
public void setFirstTabOffset(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el número de espacios entre el comienzo de una línea de texto y la primera tabulación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Obtiene o establece un entero con signo de 32 bits que especifica el tipo de procesamiento que se realiza en una cadena cuando se encuentra un prefijo de atajo de teclado (es decir, una ampersand). Básicamente, este campo especifica si se deben mostrar los prefijos de atajo de teclado que se relacionan con el texto. El valor DEBE estar definido en la enumeración HotkeyPrefix (sección 2.1.1.14).

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el tipo de procesamiento que se realiza en una cadena cuando se encuentra un prefijo de atajo de teclado (es decir, una ampersand). Básicamente, este campo especifica si se deben mostrar los prefijos de atajo de teclado que se relacionan con el texto. El valor DEBE estar definido en la enumeración HotkeyPrefix (sección 2.1.1.14).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLanguage() {#getLanguage--}
```
public short getLanguage()
```


Obtiene o establece un objeto EmfPlusLanguageIdentifier (sección 2.2.2.23) que especifica el idioma a usar para la cadena.

**Returns:**
short
### setLanguage(short value) {#setLanguage-short-}
```
public void setLanguage(short value)
```


Obtiene o establece un objeto EmfPlusLanguageIdentifier (sección 2.2.2.23) que especifica el idioma a usar para la cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getLeadingMargin() {#getLeadingMargin--}
```
public float getLeadingMargin()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la longitud del espacio a agregar a la posición inicial de una cadena. El valor predeterminado es 1/6 de pulgada; para fuentes tipográficas, el valor predeterminado es 0.

**Returns:**
float
### setLeadingMargin(float value) {#setLeadingMargin-float-}
```
public void setLeadingMargin(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la longitud del espacio a agregar a la posición inicial de una cadena. El valor predeterminado es 1/6 de pulgada; para fuentes tipográficas, el valor predeterminado es 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getLineAlign() {#getLineAlign--}
```
public int getLineAlign()
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo alinear la cadena verticalmente en el rectángulo de diseño. Este valor DEBE estar definido en la enumeración StringAlignment.

**Returns:**
int
### setLineAlign(int value) {#setLineAlign-int-}
```
public void setLineAlign(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo alinear la cadena verticalmente en el rectángulo de diseño. Este valor DEBE estar definido en la enumeración StringAlignment.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRangeCount() {#getRangeCount--}
```
public int getRangeCount()
```


Obtiene o establece un entero con signo de 32 bits que especifica el número de objetos EmfPlusCharacterRange (sección 2.2.2.8) definidos en el campo StringFormatData.

**Returns:**
int
### setRangeCount(int value) {#setRangeCount-int-}
```
public void setRangeCount(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el número de objetos EmfPlusCharacterRange (sección 2.2.2.8) definidos en el campo StringFormatData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getStringAlignment() {#getStringAlignment--}
```
public int getStringAlignment()
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo alinear la cadena horizontalmente en el rectángulo de diseño. Este valor DEBE estar definido en la enumeración StringAlignment (sección 2.1.1.29).

**Returns:**
int
### setStringAlignment(int value) {#setStringAlignment-int-}
```
public void setStringAlignment(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo alinear la cadena horizontalmente en el rectángulo de diseño. Este valor DEBE estar definido en la enumeración StringAlignment (sección 2.1.1.29).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getStringFormatData() {#getStringFormatData--}
```
public EmfPlusStringFormatData getStringFormatData()
```


Obtiene o establece un objeto EmfPlusStringFormatData (sección 2.2.2.44) que especifica datos opcionales de diseño de texto.

**Returns:**
[EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata)
### setStringFormatData(EmfPlusStringFormatData value) {#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-}
```
public void setStringFormatData(EmfPlusStringFormatData value)
```


Obtiene o establece un objeto EmfPlusStringFormatData (sección 2.2.2.44) que especifica datos opcionales de diseño de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata) |  |

### getStringFormatFlags() {#getStringFormatFlags--}
```
public long getStringFormatFlags()
```


Obtiene o establece un entero sin signo de 32 bits que especifica las opciones de diseño de texto para formato, recorte y manejo de fuentes. Este valor DEBE estar compuesto por banderas StringFormat (sección 2.1.2.8).

**Returns:**
long
### setStringFormatFlags(long value) {#setStringFormatFlags-long-}
```
public void setStringFormatFlags(long value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica las opciones de diseño de texto para formato, recorte y manejo de fuentes. Este valor DEBE estar compuesto por banderas StringFormat (sección 2.1.2.8).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getTabstopCount() {#getTabstopCount--}
```
public int getTabstopCount()
```


Obtiene o establece un entero con signo de 32 bits que especifica el número de tabulaciones definidas en el campo StringFormatData.

**Returns:**
int
### setTabstopCount(int value) {#setTabstopCount-int-}
```
public void setTabstopCount(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el número de tabulaciones definidas en el campo StringFormatData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTracking() {#getTracking--}
```
public float getTracking()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la proporción del espacio horizontal asignado a cada carácter en una cadena especificada respecto al ancho del carácter definido por la fuente. Valores grandes para esta propiedad indican amplio espacio entre caracteres; valores menores que 1 pueden producir superposición de caracteres. El valor predeterminado es 1.03; para fuentes tipográficas, el valor predeterminado es 1.00.

**Returns:**
float
### setTracking(float value) {#setTracking-float-}
```
public void setTracking(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la proporción del espacio horizontal asignado a cada carácter en una cadena especificada respecto al ancho del carácter definido por la fuente. Valores grandes para esta propiedad indican amplio espacio entre caracteres; valores menores que 1 pueden producir superposición de caracteres. El valor predeterminado es 1.03; para fuentes tipográficas, el valor predeterminado es 1.00.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getTrailingMargin() {#getTrailingMargin--}
```
public float getTrailingMargin()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la longitud del espacio que se debe dejar después de una cadena. El valor predeterminado es 1/6 de pulgada; para fuentes tipográficas, el valor predeterminado es 0.

**Returns:**
float
### setTrailingMargin(float value) {#setTrailingMargin-float-}
```
public void setTrailingMargin(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica la longitud del espacio que se debe dejar después de una cadena. El valor predeterminado es 1/6 de pulgada; para fuentes tipográficas, el valor predeterminado es 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Obtiene o establece cómo recortar caracteres de una cadena que es demasiado grande para caber en un rectángulo de diseño. Este valor DEBE estar definido en la enumeración StringTrimming (sección 2.1.1.31).

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Obtiene o establece cómo recortar caracteres de una cadena que es demasiado grande para caber en un rectángulo de diseño. Este valor DEBE estar definido en la enumeración StringTrimming (sección 2.1.1.31).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

