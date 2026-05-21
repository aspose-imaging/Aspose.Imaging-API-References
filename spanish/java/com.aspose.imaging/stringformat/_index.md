---
title: "StringFormat"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Encapsula información de diseño de texto como alineación, orientación y tabulaciones, manipulaciones de visualización como inserción de elipsis y sustitución de dígitos nacionales y características OpenType."
type: docs
weight: 112
url: /es/java/com.aspose.imaging/stringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Encapsula información de diseño de texto (como alineación, orientación y tabulaciones), manipulaciones de visualización (como inserción de elipsis y sustitución de dígitos nacionales) y características OpenType. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [StringFormat()](#StringFormat--) | Inicializa un nuevo objeto `com.aspose.imaging.StringFormat`. |
| [StringFormat(int options)](#StringFormat-int-) | Inicializa un nuevo objeto `com.aspose.imaging.StringFormat` con la enumeración `com.aspose.imaging.StringFormatFlags` especificada y el idioma. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.imaging.StringFormat-) | Inicializa un nuevo objeto `com.aspose.imaging.StringFormat` a partir del objeto `com.aspose.imaging.StringFormat` existente especificado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getGenericDefault()](#getGenericDefault--) | Obtiene un objeto genérico predeterminado `com.aspose.imaging.StringFormat`. |
| [getGenericTypographic()](#getGenericTypographic--) | Obtiene un objeto tipográfico genérico `com.aspose.imaging.StringFormat`. |
| [getFormatFlags()](#getFormatFlags--) | Obtiene una enumeración `com.aspose.imaging.StringFormatFlags` que contiene información de formato. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Establece una enumeración `com.aspose.imaging.StringFormatFlags` que contiene información de formato. |
| [getAlignment()](#getAlignment--) | Obtiene información de alineación de texto en el plano vertical. |
| [setAlignment(int value)](#setAlignment-int-) | Establece información de alineación de texto en el plano vertical. |
| [getLineAlignment()](#getLineAlignment--) | Obtiene la alineación de línea en el plano horizontal. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Establece la alineación de línea en el plano horizontal. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Obtiene el objeto `com.aspose.imaging.HotkeyPrefix` para este objeto `com.aspose.imaging.StringFormat`. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Establece el objeto `com.aspose.imaging.HotkeyPrefix` para este objeto `com.aspose.imaging.StringFormat`. |
| [getTrimming()](#getTrimming--) | Obtiene la enumeración `com.aspose.imaging.StringTrimming` para este objeto `com.aspose.imaging.StringFormat`. |
| [setTrimming(int value)](#setTrimming-int-) | Establece la enumeración `com.aspose.imaging.StringTrimming` para este objeto `com.aspose.imaging.StringFormat`. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Obtiene el método que se usará para la sustitución de dígitos. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Establece el método que se usará para la sustitución de dígitos. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Obtiene el idioma que se usa cuando los dígitos locales se sustituyen por dígitos occidentales. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Establece el idioma que se usa cuando los dígitos locales se sustituyen por dígitos occidentales. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Obtiene el número de espacios entre el inicio de una línea de texto y la primera tabulación. |
| [getTabStops()](#getTabStops--) | Obtiene una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad `P:Aspose.Imaging.getGraphics().PageUnit`. |
| [getCustomCharIdent()](#getCustomCharIdent--) | Obtiene el identificador de carácter personalizado. |
| [setCustomCharIdent(PointF value)](#setCustomCharIdent-com.aspose.imaging.PointF-) | Establece el identificador de carácter personalizado. |
| [deepClone()](#deepClone--) | Crea una clonación profunda de este objeto `com.aspose.imaging.StringFormat`. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Establece tabulaciones para este objeto `com.aspose.imaging.StringFormat`. |
| [toString()](#toString--) | Convierte este objeto `com.aspose.imaging.StringFormat` a una cadena legible por humanos. |
| [equals(Object o)](#equals-java.lang.Object-) | Comprueba si los objetos son iguales. |
| [hashCode()](#hashCode--) | Obtiene el código hash del objeto actual. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Inicializa un nuevo objeto `com.aspose.imaging.StringFormat`.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Inicializa un nuevo objeto `com.aspose.imaging.StringFormat` con la enumeración `com.aspose.imaging.StringFormatFlags` especificada y el idioma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| opciones | int | La enumeración `com.aspose.imaging.StringFormatFlags` para el nuevo objeto `com.aspose.imaging.StringFormat`. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.imaging.StringFormat-}
```
public StringFormat(StringFormat format)
```


Inicializa un nuevo objeto `com.aspose.imaging.StringFormat` a partir del objeto `com.aspose.imaging.StringFormat` existente especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.imaging/stringformat) | El objeto `com.aspose.imaging.StringFormat` del cual inicializar el nuevo objeto `com.aspose.imaging.StringFormat`. |

### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Obtiene un objeto genérico predeterminado `com.aspose.imaging.StringFormat`.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The generic default `com.aspose.imaging.StringFormat` object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Obtiene un objeto tipográfico genérico `com.aspose.imaging.StringFormat`.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - A generic typographic `com.aspose.imaging.StringFormat` object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Obtiene una enumeración `com.aspose.imaging.StringFormatFlags` que contiene información de formato.

**Returns:**
int - Una enumeración `com.aspose.imaging.StringFormatFlags` que contiene información de formato.
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Establece una enumeración `com.aspose.imaging.StringFormatFlags` que contiene información de formato.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Una enumeración `com.aspose.imaging.StringFormatFlags` que contiene información de formato. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Obtiene información de alineación de texto en el plano vertical.

**Returns:**
int - Una enumeración `com.aspose.imaging.StringAlignment` que especifica información de alineación de texto.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Establece información de alineación de texto en el plano vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Una enumeración `com.aspose.imaging.StringAlignment` que especifica información de alineación de texto. |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Obtiene la alineación de línea en el plano horizontal.

**Returns:**
int - Una enumeración `com.aspose.imaging.StringAlignment` que representa la alineación de línea.
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Establece la alineación de línea en el plano horizontal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Una enumeración `com.aspose.imaging.StringAlignment` que representa la alineación de línea. |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Obtiene el objeto `com.aspose.imaging.HotkeyPrefix` para este objeto `com.aspose.imaging.StringFormat`.

**Returns:**
int - El objeto `com.aspose.imaging.HotkeyPrefix` para este objeto `com.aspose.imaging.StringFormat`, el valor predeterminado es `F:Aspose.Imaging.HotkeyPrefix.None`.
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Establece el objeto `com.aspose.imaging.HotkeyPrefix` para este objeto `com.aspose.imaging.StringFormat`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El objeto `com.aspose.imaging.HotkeyPrefix` para este objeto `com.aspose.imaging.StringFormat`, el valor predeterminado es `F:Aspose.Imaging.HotkeyPrefix.None`. |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Obtiene la enumeración `com.aspose.imaging.StringTrimming` para este objeto `com.aspose.imaging.StringFormat`.

**Returns:**
int - Una enumeración `com.aspose.imaging.StringTrimming` que indica cómo se recorta el texto dibujado con este objeto `com.aspose.imaging.StringFormat` cuando supera los bordes del rectángulo de diseño.
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Establece la enumeración `com.aspose.imaging.StringTrimming` para este objeto `com.aspose.imaging.StringFormat`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Una enumeración `com.aspose.imaging.StringTrimming` que indica cómo se recorta el texto dibujado con este objeto `com.aspose.imaging.StringFormat` cuando supera los bordes del rectángulo de diseño. |

### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Obtiene el método que se usará para la sustitución de dígitos.

**Returns:**
int - Un valor de enumeración `com.aspose.imaging.StringDigitSubstitute` que especifica cómo sustituir caracteres en una cadena que no se pueden mostrar porque no son compatibles con la fuente actual.

El setter se introduce para el método obsoleto SetDigitSubstitution.
### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Establece el método que se usará para la sustitución de dígitos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | Un valor de enumeración `com.aspose.imaging.StringDigitSubstitute` que especifica cómo sustituir caracteres en una cadena que no se pueden mostrar porque no son compatibles con la fuente actual. |

El setter se introduce para el método obsoleto SetDigitSubstitution. |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Obtiene el idioma que se usa cuando los dígitos locales se sustituyen por dígitos occidentales.

**Returns:**
int - Un identificador de idioma de Soporte de Idioma Nacional (NLS) que identifica el idioma que se utilizará cuando los dígitos locales se sustituyan por dígitos occidentales. Puede pasar la propiedad `P:System.Globalization.CultureInfo.LCID` de un objeto `System.Globalization.CultureInfo` como el identificador de idioma NLS. Por ejemplo, suponga que crea y establece una configuración regional "ar-EG". Si pasa `com.aspose.imaging.StringDigitSubstitute.Traditional` al método `com.aspose.imaging.StringFormat.setDigitSubstitution(int)`, entonces los dígitos árabe-indios se sustituirán por dígitos occidentales en tiempo de visualización.
### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Establece el idioma que se usa cuando los dígitos locales se sustituyen por dígitos occidentales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Un identificador de idioma de Soporte de Idioma Nacional (NLS) que identifica el idioma que se utilizará cuando los dígitos locales se sustituyan por dígitos occidentales. Puede pasar la propiedad `P:System.Globalization.CultureInfo.LCID` de un objeto `System.Globalization.CultureInfo` como el identificador de idioma NLS. Por ejemplo, suponga que crea y establece una configuración regional "ar-EG". Si pasa `com.aspose.imaging.StringDigitSubstitute.Traditional` al método `com.aspose.imaging.StringFormat.setDigitSubstitution(int)`, entonces los dígitos árabe-indios se sustituirán por dígitos occidentales en tiempo de visualización. |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Obtiene el número de espacios entre el inicio de una línea de texto y la primera tabulación.

**Returns:**
float - El primer desplazamiento de tabulación.

La propiedad se introduce para el método eliminado GetTabStops.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Obtiene una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad `P:Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - Las tabulaciones.

La propiedad se introduce para el método eliminado GetTabStops.
### getCustomCharIdent() {#getCustomCharIdent--}
```
public PointF getCustomCharIdent()
```


Obtiene el identificador de carácter personalizado.

Valor: El identificador de carácter personalizado.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - the custom character ident.
### setCustomCharIdent(PointF value) {#setCustomCharIdent-com.aspose.imaging.PointF-}
```
public void setCustomCharIdent(PointF value)
```


Establece el identificador de carácter personalizado.

Valor: El identificador de carácter personalizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | el identificador de carácter personalizado. |

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Crea una clonación profunda de este objeto `com.aspose.imaging.StringFormat`.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The deep clone of the current `com.aspose.imaging.StringFormat`.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Establece tabulaciones para este objeto `com.aspose.imaging.StringFormat`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstTabOffset | float | El número de espacios entre el inicio de una línea de texto y la primera tabulación. |
| tabStops | float[] | Una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad `com.aspose.imaging.Graphics.PageUnit`. |

### toString() {#toString--}
```
public String toString()
```


Convierte este objeto `com.aspose.imaging.StringFormat` a una cadena legible por humanos.

**Returns:**
java.lang.String - Una representación en forma de cadena de este objeto `com.aspose.imaging.StringFormat`.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Comprueba si los objetos son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | java.lang.Object | El otro objeto. |

**Returns:**
boolean - El resultado de la comparación de igualdad.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash del objeto actual.

**Returns:**
int - El código hash.
