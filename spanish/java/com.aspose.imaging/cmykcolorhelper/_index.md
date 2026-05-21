---
title: "CmykColorHelper"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Métodos auxiliares para trabajar con el color CMYK presentado como un valor entero de 32 bits con signo."
type: docs
weight: 19
url: /es/java/com.aspose.imaging/cmykcolorhelper/
---
**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Métodos auxiliares para trabajar con el color CMYK presentado como un valor entero de 32 bits con signo. Proporciona una API similar a la estructura [CmykColor](../../com.aspose.imaging/cmykcolor). Es más liviano porque el color CMYK se presenta simplemente como Int32 en lugar de una estructura con campos internos. Por favor, prefiera usar los métodos estáticos de esta clase cuando sea posible en lugar de la estructura obsoleta [CmykColor](../../com.aspose.imaging/cmykcolor).
## Métodos

| Método | Descripción |
| --- | --- |
| [getC(int cmyk)](#getC-int-) | Obtiene el valor del componente cian. |
| [getM(int cmyk)](#getM-int-) | Obtiene el valor del componente magenta. |
| [getY(int cmyk)](#getY-int-) | Obtiene el valor del componente amarillo. |
| [getK(int cmyk)](#getK-int-) | Obtiene el valor del componente negro. |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Crea CMYK a partir de valores de cian, magenta, amarillo y negro de 32 bits. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | La conversión de colores ARGB a colores CMYK. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Convierte ARGB a CMYK. |
| [toCmykaBytes(int[] argbPixels, int startIndex, int length)](#toCmykaBytes-int---int-int-) | Convierte ARGB a CMYKA (con transparencia). |
| [toCmyk(int argbPixel)](#toCmyk-int-) | La conversión de color ARGB a color CMYK. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.imaging.Color-) | La conversión de color ARGB a color CMYK. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.imaging.Color---) | La conversión de colores ARGB a colores CMYK. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | La conversión de colores CMYK a colores ARGB. |
| [toArgb(int cmykPixel)](#toArgb-int-) | La conversión de color CMYK a color ARGB. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | La conversión de colores CMYK a colores ARGB. |
| [toArgb32(int[] cmykPixels, boolean reuseArray)](#toArgb32-int---boolean-) | Realiza la conversión de colores CMYK a colores ARGB y los almacena en el mismo arreglo si `reuseArray` es verdadero. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | La conversión de color CMYK a color ARGB usando conversión Icc con perfiles predeterminados. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | La conversión de color CMYK a color ARGB usando conversión Icc con perfil personalizado. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados. |
| [toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int---java.io.InputStream-java.io.InputStream-) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Convierte RGB a CMYK usando perfiles ICC personalizados. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | Convierte RGB a CMYK usando perfiles ICC personalizados. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | Convierte RGB a CMYKA (con alfa) usando perfiles ICC personalizados. |
| [toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Convierte RGB a CMYKA (con alfa) usando perfiles ICC personalizados. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.imaging.Color---) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados. |
| [toCmykIcc(int[] pixels)](#toCmykIcc-int---) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados. |
| [toPsdCmykIcc(int[] pixels)](#toPsdCmykIcc-int---) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.imaging.Color-) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados. |
| [toCmykIcc(int argb)](#toCmykIcc-int-) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados. |
| [toPsdCmykIcc(int argb)](#toPsdCmykIcc-int-) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados. |
| [toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int-java.io.InputStream-java.io.InputStream-) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados. |
| [toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados. |
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Obtiene el valor del componente cian.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns:**
int - El valor del componente cian.

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

//La salida se ve así:
//Convierte RGB a CMYK sin usar perfiles ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Obtiene el valor del componente magenta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns:**
int - El valor del componente magenta.

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

//La salida se ve así:
//Convierte RGB a CMYK sin usar perfiles ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Obtiene el valor del componente amarillo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns:**
int - El valor del componente amarillo.

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

//La salida se ve así:
//Convierte RGB a CMYK sin usar perfiles ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


Obtiene el valor del componente negro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns:**
int - El valor del componente negro.

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

//La salida se ve así:
//Convierte RGB a CMYK sin usar perfiles ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Crea CMYK a partir de valores de cian, magenta, amarillo y negro de 32 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cian | int | El componente cian. Los valores válidos son de 0 a 255. |
| magenta | int | El componente magenta. Los valores válidos son de 0 a 255. |
| amarillo | int | El componente amarillo. Los valores válidos son de 0 a 255. |
| negro | int | El componente negro. Los valores válidos son de 0 a 255. |

**Returns:**
int - El color CMYK presentado como un valor entero de 32 bits.

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

//La salida se ve así:
//Convertir CMYK a RGB sin usar perfiles ICC.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


La conversión de colores ARGB a colores CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argbPixels | int[] | Los colores ARGB presentados como valores enteros de 32 bits. |

**Returns:**
int[] - Los colores CMYK presentados como valores enteros de 32 bits.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Convierte ARGB a CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argbPixels | int[] | Los colores RGB presentados como valores enteros de 32 bits. |
| startIndex | int | El índice de inicio del color RGB. |
| length | int | El número de píxeles RGB a convertir. |

**Returns:**
byte[] - Los colores CMYK presentados como una matriz de bytes.
### toCmykaBytes(int[] argbPixels, int startIndex, int length) {#toCmykaBytes-int---int-int-}
```
public static byte[] toCmykaBytes(int[] argbPixels, int startIndex, int length)
```


Convierte ARGB a CMYKA (con transparencia).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argbPixels | int[] | Los colores RGB presentados como valores enteros de 32 bits. |
| startIndex | int | El índice de inicio del color RGB. |
| length | int | El número de píxeles RGB a convertir. |

**Returns:**
byte[] - Los colores CMYK presentados como una matriz de bytes.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


La conversión de color ARGB a color CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argbPixel | int | El color ARGB presentado como un valor entero de 32 bits. |

**Returns:**
int - El color CMYK presentado como un valor entero de 32 bits.
### toCmyk(Color pixel) {#toCmyk-com.aspose.imaging.Color-}
```
public static int toCmyk(Color pixel)
```


La conversión de color ARGB a color CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | El color ARGB. |

**Returns:**
int - El color CMYK presentado como un valor entero de 32 bits.

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

//La salida se ve así:
//Convierte RGB a CMYK sin usar perfiles ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### toCmyk(Color[] pixels) {#toCmyk-com.aspose.imaging.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


La conversión de colores ARGB a colores CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Los colores ARGB. |

**Returns:**
int[] - Los colores CMYK presentados como valores enteros de 32 bits.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


La conversión de colores CMYK a colores ARGB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | int[] | Los colores CMYK presentados como valores enteros de 32 bits. |

**Returns:**
com.aspose.imaging.Color[] - Los colores ARGB.
### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


La conversión de color CMYK a color ARGB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | int | El color CMYK presentado como un valor entero de 32 bits. |

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

//La salida se ve así:
//Convertir CMYK a RGB sin usar perfiles ICC.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


La conversión de colores CMYK a colores ARGB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | int[] | Los colores CMYK presentados como valores enteros de 32 bits. |

**Returns:**
int[] - Los colores ARGB presentados como valores enteros de 32 bits.
### toArgb32(int[] cmykPixels, boolean reuseArray) {#toArgb32-int---boolean-}
```
public static int[] toArgb32(int[] cmykPixels, boolean reuseArray)
```


Realiza la conversión de colores CMYK a colores ARGB y los almacena en el mismo arreglo si `reuseArray` es verdadero. De lo contrario, se asignará un nuevo arreglo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | int[] | Los colores CMYK presentados como valores enteros de 32 bits. |
| reuseArray | boolean | si `true` el arreglo de entrada `cmykPixels` se rellenará con nuevos valores y se devolverá; de lo contrario, se asignará y devolverá un nuevo arreglo. |

**Returns:**
int[] - El nuevo arreglo asignado o `cmykPixels` rellenado con colores ARGB presentados como valores enteros de 32 bits.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | int[] | Los píxeles CMYK presentados como valores enteros de 32 bits. |

**Returns:**
com.aspose.imaging.Color[] - Los colores ARGB.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | int[] | Los colores CMYK presentados como valores enteros de 32 bits. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil Icc CMYK. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil Icc RGB. |

**Returns:**
com.aspose.imaging.Color[] - Los colores ARGB.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


La conversión de color CMYK a color ARGB usando conversión Icc con perfiles predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | int | El color CMYK presentado como un valor entero de 32 bits. |

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

// Especifique su ruta a los perfiles ICC personalizados RGB y CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Lea todos los bytes de los archivos ICC a la memoria para tener la posibilidad de restablecer el flujo del perfil de entrada antes de llamar a toCmykIcc
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

//La salida se ve así:
//Convierta CMYK a RGB usando los perfiles ICC predeterminados.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Convertir CMYK a RGB usando perfiles ICC personalizados.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversión de color CMYK a color ARGB usando conversión Icc con perfil personalizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | int | El color CMYK presentado como un valor entero de 32 bits. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil Icc CMYK. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil Icc RGB. |

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

// Especifique su ruta a los perfiles ICC personalizados RGB y CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Lea todos los bytes de los archivos ICC a la memoria para tener la posibilidad de restablecer el flujo del perfil de entrada antes de llamar a toCmykIcc
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

//La salida se ve así:
//Convierta CMYK a RGB usando los perfiles ICC predeterminados.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Convertir CMYK a RGB usando perfiles ICC personalizados.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Los colores ARGB. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil Icc RGB. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil Icc CMYK. |

**Returns:**
int[] - Los colores CMYK presentados como valores enteros de 32 bits.
### toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Los colores ARGB. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil Icc RGB. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil Icc CMYK. |

**Returns:**
int[] - Los colores CMYK presentados como valores enteros de 32 bits.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Convierte RGB a CMYK usando perfiles ICC personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Los colores RGB presentados como valores enteros de 32 bits. |
| startIndex | int | El índice de inicio del color RGB. |
| length | int | El número de píxeles RGB a convertir. |
| rgbIccStream | java.io.InputStream | El flujo del perfil RGB. |
| cmykIccStream | java.io.InputStream | El flujo del perfil CMYK. |

**Returns:**
byte[] - Los colores CMYK presentados como una matriz de bytes.
### toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


Convierte RGB a CMYK usando perfiles ICC personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Los colores RGB presentados como valores enteros de 32 bits. |
| startIndex | int | El índice de inicio del color RGB. |
| length | int | El número de píxeles RGB a convertir. |
| cmykBytes | byte[] | Los bytes Cmyk. |
| cmykOffset | int | El desplazamiento de `cmykBytes`. |
| rgbIccStream | java.io.InputStream | El flujo del perfil RGB. |
| cmykIccStream | java.io.InputStream | El flujo del perfil CMYK. |

**Returns:**
byte[] - Los colores CMYK presentados como una matriz de bytes.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


Convierte RGB a CMYKA (con alfa) usando perfiles ICC personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Los colores RGB presentados como valores enteros de 32 bits. |
| startIndex | int | El índice de inicio del color RGB. |
| length | int | El número de píxeles RGB a convertir. |
| cmykBytes | byte[] | Los bytes Cmyk. |
| cmykOffset | int | El desplazamiento de `cmykBytes`. |
| rgbIccStream | java.io.InputStream | El flujo del perfil RGB. |
| cmykIccStream | java.io.InputStream | El flujo del perfil CMYK. |

**Returns:**
byte[] - Los colores CMYK presentados como una matriz de bytes.
### toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversión de colores ARGB a colores CMYK usando la conversión Icc con perfiles personalizados. Utiliza el formato CMYK de PSD con orden de bytes KCMY y valores de canal invertidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Los colores ARGB. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil Icc RGB. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil Icc CMYK. |

**Returns:**
int[] - Los colores CMYK presentados como valores enteros de 32 bits en orden de bytes KCMY con valores de canal invertidos.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Convierte RGB a CMYKA (con alfa) usando perfiles ICC personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Los colores RGB presentados como valores enteros de 32 bits. |
| startIndex | int | El índice de inicio del color RGB. |
| length | int | El número de píxeles RGB a convertir. |
| rgbIccStream | java.io.InputStream | El flujo del perfil RGB. |
| cmykIccStream | java.io.InputStream | El flujo del perfil CMYK. |

**Returns:**
byte[] - Los colores CMYK presentados como una matriz de bytes.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.imaging.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Los colores ARGB. |

**Returns:**
int[] - Los colores CMYK presentados como valores enteros de 32 bits.
### toCmykIcc(int[] pixels) {#toCmykIcc-int---}
```
public static int[] toCmykIcc(int[] pixels)
```


La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Los colores ARGB. |

**Returns:**
int[] - Los colores CMYK presentados como valores enteros de 32 bits.
### toPsdCmykIcc(int[] pixels) {#toPsdCmykIcc-int---}
```
public static int[] toPsdCmykIcc(int[] pixels)
```


La conversión de colores ARGB a colores CMYK usando la conversión Icc con perfiles predeterminados. Utiliza el formato CMYK de PSD con orden de bytes KCMY y valores de canal invertidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Los colores ARGB. |

**Returns:**
int[] - Los colores CMYK presentados como valores enteros de 32 bits en orden de bytes KCMY con valores de canal invertidos.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.imaging.Color-}
```
public static int toCmykIcc(Color pixel)
```


La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | El color ARGB. |

**Returns:**
int - El color CMYK presentado como un valor entero de 32 bits.

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

// Especifique la ruta a los perfiles ICC de RGB y CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Lea todos los bytes de los archivos ICC a la memoria para tener la posibilidad de restablecer el flujo del perfil de entrada antes de llamar a toCmykIcc
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

//La salida se ve así:
//Convertir RGB a CMYK usando perfiles ICC predeterminados.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Convertir RGB a CMYK usando perfiles ICC personalizados.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb) {#toCmykIcc-int-}
```
public static int toCmykIcc(int argb)
```


La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb | int | El color ARGB. |

**Returns:**
int - El color CMYK presentado como un valor entero de 32 bits.
### toPsdCmykIcc(int argb) {#toPsdCmykIcc-int-}
```
public static int toPsdCmykIcc(int argb)
```


La conversión de color ARGB a color CMYK usando la conversión Icc con perfiles predeterminados. Utiliza el formato CMYK de PSD con orden de bytes KCMY y valores de canal invertidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb | int | El color ARGB. |

**Returns:**
int - El color CMYK presentado como un valor entero de 32 bits en orden de bytes KCMY con valores de canal invertidos.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | El color ARGB. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil Icc RGB. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil Icc CMYK. |

**Returns:**
int - El color CMYK presentado como un valor entero de 32 bits.

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

// Especifique la ruta a los perfiles ICC de RGB y CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Lea todos los bytes de los archivos ICC a la memoria para tener la posibilidad de restablecer el flujo del perfil de entrada antes de llamar a toCmykIcc
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

//La salida se ve así:
//Convertir RGB a CMYK usando perfiles ICC predeterminados.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Convertir RGB a CMYK usando perfiles ICC personalizados.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb | int | El color ARGB. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil Icc RGB. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil Icc CMYK. |

**Returns:**
int - El color CMYK presentado como un valor entero de 32 bits.
### toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxel | int | El color ARGB. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil Icc RGB. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil Icc CMYK. |

**Returns:**
int - Los colores CMYK presentados como valores enteros de 32 bits en orden de bytes KCMY con valores de canal invertidos.
