---
title: "CmykColorHelper"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Méthodes d'assistance pour travailler avec la couleur CMYK présentée sous forme d'entier signé de 32 bits."
type: docs
weight: 19
url: /fr/java/com.aspose.imaging/cmykcolorhelper/
---
**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Méthodes d'assistance pour travailler avec la couleur CMYK présentée sous forme d'une valeur entière signée de 32 bits. Fournit une API similaire à la structure [CmykColor](../../com.aspose.imaging/cmykcolor). Elle est plus légère car la couleur CMYK est présentée simplement comme un Int32 plutôt que comme une structure avec des champs internes. Veuillez privilégier l'utilisation des méthodes statiques de cette classe lorsque cela est possible au lieu de la structure [CmykColor](../../com.aspose.imaging/cmykcolor) obsolète.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getC(int cmyk)](#getC-int-) | Obtient la valeur du composant cyan. |
| [getM(int cmyk)](#getM-int-) | Obtient la valeur du composant magenta. |
| [getY(int cmyk)](#getY-int-) | Obtient la valeur du composant jaune. |
| [getK(int cmyk)](#getK-int-) | Obtient la valeur du composant noir. |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Crée un CMYK à partir de valeurs cyan, magenta, jaune et noir sur 32 bits. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | La conversion des couleurs ARGB en couleurs CMYK. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Convertit ARGB en CMYK. |
| [toCmykaBytes(int[] argbPixels, int startIndex, int length)](#toCmykaBytes-int---int-int-) | Convertit ARGB en CMYKA (avec transparence). |
| [toCmyk(int argbPixel)](#toCmyk-int-) | La conversion de la couleur ARGB en couleur CMYK. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.imaging.Color-) | La conversion de la couleur ARGB en couleur CMYK. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.imaging.Color---) | La conversion des couleurs ARGB en couleurs CMYK. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | La conversion des couleurs CMYK en couleurs ARGB. |
| [toArgb(int cmykPixel)](#toArgb-int-) | La conversion de la couleur CMYK en couleur ARGB. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | La conversion des couleurs CMYK en couleurs ARGB. |
| [toArgb32(int[] cmykPixels, boolean reuseArray)](#toArgb32-int---boolean-) | Effectue la conversion des couleurs CMYK en couleurs ARGB et les stocke dans le même tableau si `reuseArray` est vrai. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | La conversion des couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | La conversion des couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec des profils personnalisés. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | La conversion de la couleur CMYK en ARGB Color en utilisant la conversion Icc avec les profils par défaut. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | La conversion de la couleur CMYK en couleur ARGB en utilisant la conversion Icc avec un profil personnalisé. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-) | La conversion des couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int---java.io.InputStream-java.io.InputStream-) | La conversion des couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Convertit RGB en CMYK en utilisant des profils ICC personnalisés. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | Convertit RGB en CMYK en utilisant des profils ICC personnalisés. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | Convertit RGB en CMYKA (avec alpha) en utilisant des profils ICC personnalisés. |
| [toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-) | La conversion des couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Convertit RGB en CMYKA (avec alpha) en utilisant des profils ICC personnalisés. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.imaging.Color---) | La conversion des couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [toCmykIcc(int[] pixels)](#toCmykIcc-int---) | La conversion des couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [toPsdCmykIcc(int[] pixels)](#toPsdCmykIcc-int---) | La conversion des couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.imaging.Color-) | La conversion de la couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [toCmykIcc(int argb)](#toCmykIcc-int-) | La conversion de la couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [toPsdCmykIcc(int argb)](#toPsdCmykIcc-int-) | La conversion de la couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-) | La conversion de la couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int-java.io.InputStream-java.io.InputStream-) | La conversion de la couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés. |
| [toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-) | La conversion de la couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés. |
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Obtient la valeur du composant cyan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmyk | int | La couleur CMYK présentée comme une valeur entière 32 bits. |

**Returns:**
int - La valeur du composant cyan.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//Le résultat ressemble à ceci :
//Convertir RGB en CMYK sans utiliser de profils ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Obtient la valeur du composant magenta.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmyk | int | La couleur CMYK présentée comme une valeur entière 32 bits. |

**Returns:**
int - La valeur du composant magenta.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//Le résultat ressemble à ceci :
//Convertir RGB en CMYK sans utiliser de profils ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Obtient la valeur du composant jaune.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmyk | int | La couleur CMYK présentée comme une valeur entière 32 bits. |

**Returns:**
int - La valeur du composant jaune.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//Le résultat ressemble à ceci :
//Convertir RGB en CMYK sans utiliser de profils ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


Obtient la valeur du composant noir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmyk | int | La couleur CMYK présentée comme une valeur entière 32 bits. |

**Returns:**
int - La valeur du composant noir.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//Le résultat ressemble à ceci :
//Convertir RGB en CMYK sans utiliser de profils ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Crée un CMYK à partir de valeurs cyan, magenta, jaune et noir sur 32 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cyan | int | Le composant cyan. Les valeurs valides sont de 0 à 255. |
| magenta | int | Le composant magenta. Les valeurs valides sont de 0 à 255. |
| jaune | int | Le composant jaune. Les valeurs valides sont de 0 à 255. |
| noir | int | Le composant noir. Les valeurs valides sont de 0 à 255. |

**Returns:**
int - La couleur CMYK présentée comme une valeur entière de 32 bits.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts in a fast manner following straightforward formulas without using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB without using ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgb(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, (int) rgbColor.getB() & 0xff);
}

//Le résultat ressemble à ceci :
//Convertir le CMYK en RGB sans utiliser de profils ICC.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


La conversion des couleurs ARGB en couleurs CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argbPixels | int[] | Les couleurs ARGB présentées comme des valeurs entières de 32 bits. |

**Returns:**
int[] - Les couleurs CMYK présentées comme des valeurs entières de 32 bits.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Convertit ARGB en CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argbPixels | int[] | Les couleurs RGB présentées comme des valeurs entières de 32 bits. |
| startIndex | int | L'index de départ de la couleur RGB. |
| length | int | Le nombre de pixels RGB à convertir. |

**Returns:**
byte[] - Les couleurs CMYK présentées sous forme de tableau d'octets.
### toCmykaBytes(int[] argbPixels, int startIndex, int length) {#toCmykaBytes-int---int-int-}
```
public static byte[] toCmykaBytes(int[] argbPixels, int startIndex, int length)
```


Convertit ARGB en CMYKA (avec transparence).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argbPixels | int[] | Les couleurs RGB présentées comme des valeurs entières de 32 bits. |
| startIndex | int | L'index de départ de la couleur RGB. |
| length | int | Le nombre de pixels RGB à convertir. |

**Returns:**
byte[] - Les couleurs CMYK présentées sous forme de tableau d'octets.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


La conversion de la couleur ARGB en couleur CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argbPixel | int | La couleur ARGB présentée sous forme de valeur entière 32 bits. |

**Returns:**
int - La couleur CMYK présentée comme une valeur entière de 32 bits.
### toCmyk(Color pixel) {#toCmyk-com.aspose.imaging.Color-}
```
public static int toCmyk(Color pixel)
```


La conversion de la couleur ARGB en couleur CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | La couleur ARGB. |

**Returns:**
int - La couleur CMYK présentée comme une valeur entière de 32 bits.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//Le résultat ressemble à ceci :
//Convertir RGB en CMYK sans utiliser de profils ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### toCmyk(Color[] pixels) {#toCmyk-com.aspose.imaging.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


La conversion des couleurs ARGB en couleurs CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Les couleurs ARGB. |

**Returns:**
int[] - Les couleurs CMYK présentées comme des valeurs entières de 32 bits.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


La conversion des couleurs CMYK en couleurs ARGB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |

**Returns:**
com.aspose.imaging.Color[] - Les couleurs ARGB.
### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


La conversion de la couleur CMYK en couleur ARGB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | int | La couleur CMYK présentée comme une valeur entière 32 bits. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The ARGB color.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts in a fast manner following straightforward formulas without using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB without using ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgb(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, (int) rgbColor.getB() & 0xff);
}

//Le résultat ressemble à ceci :
//Convertir le CMYK en RGB sans utiliser de profils ICC.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


La conversion des couleurs CMYK en couleurs ARGB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |

**Returns:**
int[] - Les couleurs ARGB présentées sous forme de valeurs entières 32 bits.
### toArgb32(int[] cmykPixels, boolean reuseArray) {#toArgb32-int---boolean-}
```
public static int[] toArgb32(int[] cmykPixels, boolean reuseArray)
```


Effectue la conversion des couleurs CMYK en couleurs ARGB et les stocke dans le même tableau si `reuseArray` est vrai. Sinon, un nouveau tableau sera alloué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |
| reuseArray | boolean | si `true` le tableau d'entrée `cmykPixels` sera re-rempli avec de nouvelles valeurs et retourné; sinon un nouveau tableau sera alloué et retourné. |

**Returns:**
int[] - Le nouveau tableau alloué ou `cmykPixels` rempli de couleurs ARGB présentées sous forme de valeurs entières 32 bits.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


La conversion des couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | Les pixels CMYK présentés sous forme de valeurs entières 32 bits. |

**Returns:**
com.aspose.imaging.Color[] - Les couleurs ARGB.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversion des couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil Icc CMYK. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil Icc RGB. |

**Returns:**
com.aspose.imaging.Color[] - Les couleurs ARGB.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


La conversion de la couleur CMYK en ARGB Color en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | int | La couleur CMYK présentée comme une valeur entière 32 bits. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The ARGB color.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB using default ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
}

// Spécifiez le chemin vers les profils ICC RGB et CMYK personnalisés.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Lisez tous les octets des fichiers ICC en mémoire afin de pouvoir réinitialiser le flux de profil d'entrée avant d'appeler toCmykIcc.
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (int cmykColor : cmykColors) {
        com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

        System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//Le résultat ressemble à ceci :
//Convertissez le CMYK en RGB en utilisant les profils ICC par défaut.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Convertir le CMYK en RGB en utilisant des profils ICC personnalisés.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversion de la couleur CMYK en couleur ARGB en utilisant la conversion Icc avec un profil personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | int | La couleur CMYK présentée comme une valeur entière 32 bits. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil Icc CMYK. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil Icc RGB. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The ARGB color.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB using default ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
}

// Spécifiez le chemin vers les profils ICC RGB et CMYK personnalisés.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Lisez tous les octets des fichiers ICC en mémoire afin de pouvoir réinitialiser le flux de profil d'entrée avant d'appeler toCmykIcc.
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (int cmykColor : cmykColors) {
        com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

        System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//Le résultat ressemble à ceci :
//Convertissez le CMYK en RGB en utilisant les profils ICC par défaut.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Convertir le CMYK en RGB en utilisant des profils ICC personnalisés.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversion des couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Les couleurs ARGB. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil Icc RGB. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil Icc CMYK. |

**Returns:**
int[] - Les couleurs CMYK présentées comme des valeurs entières de 32 bits.
### toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversion des couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Les couleurs ARGB. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil Icc RGB. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil Icc CMYK. |

**Returns:**
int[] - Les couleurs CMYK présentées comme des valeurs entières de 32 bits.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Convertit RGB en CMYK en utilisant des profils ICC personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Les couleurs RGB présentées comme des valeurs entières de 32 bits. |
| startIndex | int | L'index de départ de la couleur RGB. |
| length | int | Le nombre de pixels RGB à convertir. |
| rgbIccStream | java.io.InputStream | Le flux du profil RGB. |
| cmykIccStream | java.io.InputStream | Le flux du profil CMYK. |

**Returns:**
byte[] - Les couleurs CMYK présentées sous forme de tableau d'octets.
### toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


Convertit RGB en CMYK en utilisant des profils ICC personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Les couleurs RGB présentées comme des valeurs entières de 32 bits. |
| startIndex | int | L'index de départ de la couleur RGB. |
| length | int | Le nombre de pixels RGB à convertir. |
| cmykBytes | byte[] | Les octets Cmyk. |
| cmykOffset | int | Le décalage `cmykBytes`. |
| rgbIccStream | java.io.InputStream | Le flux du profil RGB. |
| cmykIccStream | java.io.InputStream | Le flux du profil CMYK. |

**Returns:**
byte[] - Les couleurs CMYK présentées sous forme de tableau d'octets.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


Convertit RGB en CMYKA (avec alpha) en utilisant des profils ICC personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Les couleurs RGB présentées comme des valeurs entières de 32 bits. |
| startIndex | int | L'index de départ de la couleur RGB. |
| length | int | Le nombre de pixels RGB à convertir. |
| cmykBytes | byte[] | Les octets Cmyk. |
| cmykOffset | int | Le décalage `cmykBytes`. |
| rgbIccStream | java.io.InputStream | Le flux du profil RGB. |
| cmykIccStream | java.io.InputStream | Le flux du profil CMYK. |

**Returns:**
byte[] - Les couleurs CMYK présentées sous forme de tableau d'octets.
### toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversion des couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils personnalisés. Utilise le format CMYK PSD ordre d'octets KCMY avec des valeurs de canal inversées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Les couleurs ARGB. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil Icc RGB. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil Icc CMYK. |

**Returns:**
int[] - Les couleurs CMYK présentées sous forme de valeurs entières 32 bits dans l'ordre d'octets KCMY avec des valeurs de canal inversées.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Convertit RGB en CMYKA (avec alpha) en utilisant des profils ICC personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Les couleurs RGB présentées comme des valeurs entières de 32 bits. |
| startIndex | int | L'index de départ de la couleur RGB. |
| length | int | Le nombre de pixels RGB à convertir. |
| rgbIccStream | java.io.InputStream | Le flux du profil RGB. |
| cmykIccStream | java.io.InputStream | Le flux du profil CMYK. |

**Returns:**
byte[] - Les couleurs CMYK présentées sous forme de tableau d'octets.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.imaging.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


La conversion des couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Les couleurs ARGB. |

**Returns:**
int[] - Les couleurs CMYK présentées comme des valeurs entières de 32 bits.
### toCmykIcc(int[] pixels) {#toCmykIcc-int---}
```
public static int[] toCmykIcc(int[] pixels)
```


La conversion des couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Les couleurs ARGB. |

**Returns:**
int[] - Les couleurs CMYK présentées comme des valeurs entières de 32 bits.
### toPsdCmykIcc(int[] pixels) {#toPsdCmykIcc-int---}
```
public static int[] toPsdCmykIcc(int[] pixels)
```


La conversion des couleurs ARGB en couleurs CMYK en utilisant la conversion Icc avec des profils par défaut. Utilise le format CMYK PSD ordre d'octets KCMY avec des valeurs de canal inversées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Les couleurs ARGB. |

**Returns:**
int[] - Les couleurs CMYK présentées sous forme de valeurs entières 32 bits dans l'ordre d'octets KCMY avec des valeurs de canal inversées.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.imaging.Color-}
```
public static int toCmykIcc(Color pixel)
```


La conversion de la couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | La couleur ARGB. |

**Returns:**
int - La couleur CMYK présentée comme une valeur entière de 32 bits.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts using ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK using default ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

// Spécifiez le chemin vers les profils ICC RGB et CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Lisez tous les octets des fichiers ICC en mémoire afin de pouvoir réinitialiser le flux de profil d'entrée avant d'appeler toCmykIcc.
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (com.aspose.imaging.Color rgbColor : rgbColors) {

        int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

        System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//Le résultat ressemble à ceci :
//Convertir le RGB en CMYK en utilisant les profils ICC par défaut.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Convertir le RGB en CMYK en utilisant des profils ICC personnalisés.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb) {#toCmykIcc-int-}
```
public static int toCmykIcc(int argb)
```


La conversion de la couleur ARGB en couleur CMYK en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argb | int | La couleur ARGB. |

**Returns:**
int - La couleur CMYK présentée comme une valeur entière de 32 bits.
### toPsdCmykIcc(int argb) {#toPsdCmykIcc-int-}
```
public static int toPsdCmykIcc(int argb)
```


La conversion d'une couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils par défaut. Utilise le format CMYK PSD ordre d'octets KCMY avec des valeurs de canal inversées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argb | int | La couleur ARGB. |

**Returns:**
int - La couleur CMYK présentée comme une valeur entière 32 bits dans l'ordre d'octets KCMY avec des valeurs de canal inversées.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversion de la couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | La couleur ARGB. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil Icc RGB. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil Icc CMYK. |

**Returns:**
int - La couleur CMYK présentée comme une valeur entière de 32 bits.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts using ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK using default ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

// Spécifiez le chemin vers les profils ICC RGB et CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Lisez tous les octets des fichiers ICC en mémoire afin de pouvoir réinitialiser le flux de profil d'entrée avant d'appeler toCmykIcc.
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (com.aspose.imaging.Color rgbColor : rgbColors) {

        int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

        System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//Le résultat ressemble à ceci :
//Convertir le RGB en CMYK en utilisant les profils ICC par défaut.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Convertir le RGB en CMYK en utilisant des profils ICC personnalisés.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversion de la couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argb | int | La couleur ARGB. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil Icc RGB. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil Icc CMYK. |

**Returns:**
int - La couleur CMYK présentée comme une valeur entière de 32 bits.
### toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversion de la couleur ARGB en couleur CMYK en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixel | int | La couleur ARGB. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil Icc RGB. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil Icc CMYK. |

**Returns:**
int - Les couleurs CMYK présentées comme des valeurs entières 32 bits dans l'ordre d'octets KCMY avec des valeurs de canal inversées.
