---
title: "CmykColor"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El color CMYK del píxel."
type: docs
weight: 18
url: /es/java/com.aspose.imaging/cmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

El color CMYK del píxel.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEmpty()](#getEmpty--) | Obtiene el vacío. |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Crea una estructura `CmykColor` a partir de valores de cian, magenta, amarillo y negro de 32 bits. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | La conversión de color ARGB de 32 bits a CMYKColor. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.imaging.CmykColor---) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.imaging.CmykColor---) | La conversión de CMYKColor a Color ARGB de 32 bits usando conversión icc con perfiles predeterminados. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | La conversión de ARGB de 32 bits a CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.imaging.CmykColor-) | La conversión de CMYKColor a Color. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.imaging.CmykColor---) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.imaging.CmykColor-) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-) | La conversión de CMYKColor a Color usando conversión icc. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-) | La conversión de CMYKColor a Color usando conversión icc. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-) |  |
| [getC()](#getC--) | Obtiene el valor del componente cian de esta estructura `com.com.aspose.imaging.Color`. |
| [getM()](#getM--) | Obtiene el valor del componente magenta de esta estructura `com.com.aspose.imaging.Color`. |
| [getY()](#getY--) | Obtiene el valor del componente amarillo de esta estructura `com.com.aspose.imaging.Color`. |
| [getK()](#getK--) | Obtiene el valor del componente negro de esta estructura `com.com.aspose.imaging.Color`. |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si esta estructura `com.com.aspose.imaging.Color` no está inicializada. |
| [hashCode()](#hashCode--) | El código hash. |
| [toValue()](#toValue--) | El valor to. |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.imaging.CmykColor-) |  |
| [Clone()](#Clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### CmykColor() {#CmykColor--}
```
public CmykColor()
```


### getEmpty() {#getEmpty--}
```
public static CmykColor getEmpty()
```


Obtiene el vacío.

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Crea una estructura `CmykColor` a partir de valores de cian, magenta, amarillo y negro de 32 bits. Este método está obsoleto. Por favor, use un CmykColorHelper\\#fromComponents(int, int, int, int) más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cian | int | El componente cian. Los valores válidos son de 0 a 255. |
| magenta | int | El componente magenta. Los valores válidos son de 0 a 255. |
| amarillo | int | El componente amarillo. Los valores válidos son de 0 a 255. |
| negro | int | El componente negro. Los valores válidos son de 0 a 255. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The `CmykColor`.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


La conversión de color ARGB de 32 bits a CMYKColor. Este método está obsoleto. Por favor, use un `CmykColorHelper.toCmyk(int[])` más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argbPixels | int[] | Los píxeles del formato ARGB de 32 bits. |

**Returns:**
com.aspose.imaging.CmykColor[] - El [CmykColor](../../com.aspose.imaging/cmykcolor)[].
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.imaging.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. Este método está obsoleto. Por favor, use un [CmykColorHelper.toArgb(int)](../../com.aspose.imaging/cmykcolorhelper\\#toArgb-int-)\\} más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Los píxeles del tipo CMYKColor en formato CMYK. |

**Returns:**
com.aspose.imaging.Color[] - La matriz de los colores ARGB.
### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.imaging.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


La conversión de CMYKColor a Color ARGB de 32 bits usando conversión icc con perfiles predeterminados. Este método está obsoleto. Por favor, use un `CmykColorHelper.toArgb32(int[])` más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Los píxeles del tipo CMYKColor en formato CMYK. |

**Returns:**
int[] - La matriz del color ARGB de 32 bits.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


La conversión de ARGB de 32 bits a CMYKColor. Este método está obsoleto. Por favor, use un `CmykColorHelper.toCmyk(int)` más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argbPixel | int | El píxel del formato ARGB de 32 bits. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The [CmykColor](../../com.aspose.imaging/cmykcolor).
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.imaging.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


La conversión de CMYKColor a Color. Este método está obsoleto. Por favor, use un `CmykColorHelper.toArgb(int)` más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Los píxeles del tipo CMYKColor en formato CMYK. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.imaging.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. Este método está obsoleto. Por favor, use un CmykColorHelper\\#toArgbIcc(int[]) más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Los píxeles del tipo CMYKColor en formato CMYK. |

**Returns:**
com.aspose.imaging.Color[] - El `com.com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.imaging.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. Este método está obsoleto. Por favor, use un `CmykColorHelper.toArgbIcc(int)` más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | El píxel del tipo CMYKColor en formato CMYK. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversión de CMYKColor a Color usando conversión icc. Este método está obsoleto. Por favor, use un `CmykColorHelper.toArgbIcc(int[], InputStream, InputStream)` más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Los píxeles del tipo CMYKColor en formato CMYK. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil icc cmyk. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil icc rgb. |

**Returns:**
com.aspose.imaging.Color[] - El `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversión de CMYKColor a Color usando conversión icc. Este método está obsoleto. Por favor, use un `CmykColorHelper.toArgbIcc(int, Stream, Stream)` más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | El píxel del tipo CMYKColor en formato CMYK. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil icc cmyk. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil icc rgb. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

**Returns:**
boolean
### getC() {#getC--}
```
public byte getC()
```


Obtiene el valor del componente cian de esta estructura `com.com.aspose.imaging.Color`.

**Returns:**
byte - El valor del componente cian de este `com.com.aspose.imaging.Color`.
### getM() {#getM--}
```
public byte getM()
```


Obtiene el valor del componente magenta de esta estructura `com.com.aspose.imaging.Color`.

**Returns:**
byte - El valor del componente magenta de este `com.com.aspose.imaging.Color`.
### getY() {#getY--}
```
public byte getY()
```


Obtiene el valor del componente amarillo de esta estructura `com.com.aspose.imaging.Color`.

**Returns:**
byte - El valor del componente amarillo de este `com.com.aspose.imaging.Color`.
### getK() {#getK--}
```
public byte getK()
```


Obtiene el valor del componente negro de esta estructura `com.com.aspose.imaging.Color`.

Valor: El valor del componente negro de este `com.com.aspose.imaging.Color`.

**Returns:**
byte
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtiene un valor que indica si esta estructura `com.com.aspose.imaging.Color` no está inicializada.

**Returns:**
boolean - Esta propiedad devuelve verdadero si este color no está inicializado; de lo contrario, falso.
### hashCode() {#hashCode--}
```
public int hashCode()
```


El código hash.

**Returns:**
int - El `int`.
### toValue() {#toValue--}
```
public long toValue()
```


El valor to.

**Returns:**
long - El valor CMYK largo.
### CloneTo(CmykColor that) {#CloneTo-com.aspose.imaging.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

### Clone() {#Clone--}
```
public CmykColor Clone()
```




**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
