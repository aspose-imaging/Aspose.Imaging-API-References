---
title: "CmykColor"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La couleur CMYK du pixel."
type: docs
weight: 18
url: /fr/java/com.aspose.imaging/cmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

La couleur CMYK du pixel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEmpty()](#getEmpty--) | Obtient la valeur vide. |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Crée une structure `CmykColor` à partir de valeurs cyan, magenta, jaune et noir sur 32 bits. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | La conversion d'une couleur ARGB 32 bits vers CMYKColor. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.imaging.CmykColor---) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut. |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.imaging.CmykColor---) | La conversion de CMYKColor vers une couleur ARGB 32 bits en utilisant la conversion icc avec les profils par défaut. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | La conversion d'ARGB 32 bits vers CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.imaging.CmykColor-) | La conversion de CMYKColor vers Color. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.imaging.CmykColor---) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.imaging.CmykColor-) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-) | La conversion de CMYKColor vers Color en utilisant la conversion icc. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-) | La conversion de CMYKColor vers Color en utilisant la conversion icc. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-) |  |
| [getC()](#getC--) | Obtient la valeur du composant cyan de cette structure `com.com.aspose.imaging.Color`. |
| [getM()](#getM--) | Obtient la valeur du composant magenta de cette structure `com.com.aspose.imaging.Color`. |
| [getY()](#getY--) | Obtient la valeur du composant jaune de cette structure `com.com.aspose.imaging.Color`. |
| [getK()](#getK--) | Obtient la valeur du composant noir de cette structure `com.com.aspose.imaging.Color`. |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si cette structure `com.com.aspose.imaging.Color` n'est pas initialisée. |
| [hashCode()](#hashCode--) | Le code de hachage. |
| [toValue()](#toValue--) | La valeur to. |
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


Obtient la valeur vide.

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Crée une structure `CmykColor` à partir de valeurs cyan, magenta, jaune et noir sur 32 bits. Cette méthode est obsolète. Veuillez utiliser le plus efficace CmykColorHelper\#fromComponents(int, int, int, int).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cyan | int | Le composant cyan. Les valeurs valides sont de 0 à 255. |
| magenta | int | Le composant magenta. Les valeurs valides sont de 0 à 255. |
| jaune | int | Le composant jaune. Les valeurs valides sont de 0 à 255. |
| noir | int | Le composant noir. Les valeurs valides sont de 0 à 255. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The `CmykColor`.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


La conversion d'une couleur ARGB 32 bits vers CMYKColor. Cette méthode est obsolète. Veuillez utiliser le plus efficace `CmykColorHelper.toCmyk(int[])`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argbPixels | int[] | Les pixels au format ARGB 32 bits. |

**Returns:**
com.aspose.imaging.CmykColor[] - Le [CmykColor](../../com.aspose.imaging/cmykcolor)[].
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.imaging.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser le plus efficace [CmykColorHelper.toArgb(int)](../../com.aspose.imaging/cmykcolorhelper\#toArgb-int-)\}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Les pixels du type CMYKColor au format CMYK. |

**Returns:**
com.aspose.imaging.Color[] - Le tableau des couleurs ARGB.
### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.imaging.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


La conversion de CMYKColor vers la couleur ARGB 32 bits en utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser le plus efficace `CmykColorHelper.toArgb32(int[])`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Les pixels du type CMYKColor au format CMYK. |

**Returns:**
int[] - Le tableau de la couleur ARGB 32 bits.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


La conversion d'ARGB 32 bits vers CMYKColor. Cette méthode est obsolète. Veuillez utiliser le plus efficace `CmykColorHelper.toCmyk(int)`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argbPixel | int | Le pixel au format ARGB 32 bits. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The [CmykColor](../../com.aspose.imaging/cmykcolor).
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.imaging.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


La conversion de CMYKColor vers Color. Cette méthode est obsolète. Veuillez utiliser le plus efficace `CmykColorHelper.toArgb(int)`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Les pixels du type CMYKColor au format CMYK. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.imaging.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser le plus efficace CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Les pixels du type CMYKColor au format CMYK. |

**Returns:**
com.aspose.imaging.Color[] - Le `com.com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.imaging.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser le plus efficace `CmykColorHelper.toArgbIcc(int)`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Le pixel du type CMYKColor au format CMYK. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversion de CMYKColor vers Color en utilisant la conversion icc. Cette méthode est obsolète. Veuillez utiliser le plus efficace `CmykColorHelper.toArgbIcc(int[], InputStream, InputStream)`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Les pixels du type CMYKColor au format CMYK. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil icc cmyk. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil icc rgb. |

**Returns:**
com.aspose.imaging.Color[] - Le `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversion de CMYKColor vers Color en utilisant la conversion icc. Cette méthode est obsolète. Veuillez utiliser le plus efficace `CmykColorHelper.toArgbIcc(int, Stream, Stream)`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Le pixel du type CMYKColor au format CMYK. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil icc cmyk. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil icc rgb. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

**Returns:**
boolean
### getC() {#getC--}
```
public byte getC()
```


Obtient la valeur du composant cyan de cette structure `com.com.aspose.imaging.Color`.

**Returns:**
byte - La valeur du composant cyan de ce `com.com.aspose.imaging.Color`.
### getM() {#getM--}
```
public byte getM()
```


Obtient la valeur du composant magenta de cette structure `com.com.aspose.imaging.Color`.

**Returns:**
byte - La valeur du composant magenta de ce `com.com.aspose.imaging.Color`.
### getY() {#getY--}
```
public byte getY()
```


Obtient la valeur du composant jaune de cette structure `com.com.aspose.imaging.Color`.

**Returns:**
byte - La valeur du composant jaune de ce `com.com.aspose.imaging.Color`.
### getK() {#getK--}
```
public byte getK()
```


Obtient la valeur du composant noir de cette structure `com.com.aspose.imaging.Color`.

Valeur : La valeur du composant noir de ce `com.com.aspose.imaging.Color`.

**Returns:**
byte
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtient une valeur indiquant si cette structure `com.com.aspose.imaging.Color` n'est pas initialisée.

**Returns:**
boolean - Cette propriété renvoie vrai si cette couleur n'est pas initialisée ; sinon, faux.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Le code de hachage.

**Returns:**
int - Le `int`.
### toValue() {#toValue--}
```
public long toValue()
```


La valeur to.

**Returns:**
long - La valeur CMYK longue.
### CloneTo(CmykColor that) {#CloneTo-com.aspose.imaging.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
