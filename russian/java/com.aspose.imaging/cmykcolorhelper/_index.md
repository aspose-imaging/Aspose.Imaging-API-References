---
title: "CmykColorHelper"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Вспомогательные методы для работы с CMYK‑цветом, представленным как знаковое 32‑битное целое значение."
type: docs
weight: 19
url: /ru/java/com.aspose.imaging/cmykcolorhelper/
---
**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Вспомогательные методы для работы с цветом CMYK, представленным как знаковое 32‑битное целое значение. Предоставляет аналогичный API, как у структуры [CmykColor](../../com.aspose.imaging/cmykcolor). Он более лёгкий, потому что цвет CMYK представлен просто как Int32, а не как структура с внутренними полями. По возможности предпочтительно использовать статические методы этого класса вместо устаревшей структуры [CmykColor](../../com.aspose.imaging/cmykcolor).
## Методы

| Метод | Описание |
| --- | --- |
| [getC(int cmyk)](#getC-int-) | Получает значение компоненты циана. |
| [getM(int cmyk)](#getM-int-) | Получает значение компоненты мадженты. |
| [getY(int cmyk)](#getY-int-) | Получает значение желтой компоненты. |
| [getK(int cmyk)](#getK-int-) | Получает значение черной компоненты. |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Создаёт CMYK из 32‑битных значений циана, мадженты, желтого и черного. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Преобразование из цветов ARGB в цвета CMYK. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Преобразует ARGB в CMYK. |
| [toCmykaBytes(int[] argbPixels, int startIndex, int length)](#toCmykaBytes-int---int-int-) | Преобразует ARGB в CMYKA (с прозрачностью). |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Преобразование из цвета ARGB в цвет CMYK. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.imaging.Color-) | Преобразование из цвета ARGB в цвет CMYK. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.imaging.Color---) | Преобразование из цветов ARGB в цвета CMYK. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | Преобразование из цветов CMYK в цвета ARGB. |
| [toArgb(int cmykPixel)](#toArgb-int-) | Преобразование из цвета CMYK в цвет ARGB. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | Преобразование из цветов CMYK в цвета ARGB. |
| [toArgb32(int[] cmykPixels, boolean reuseArray)](#toArgb32-int---boolean-) | Выполняет преобразование из цветов CMYK в цвета ARGB и сохраняет их в тот же массив, если `reuseArray` истинно. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | Преобразование из цветов CMYK в цвета ARGB с использованием Icc преобразования и стандартных профилей. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | Преобразование из цветов CMYK в цвета ARGB с использованием Icc преобразования и пользовательских профилей. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | Преобразование из цвета CMYK в цвет ARGB с использованием Icc преобразования и стандартных профилей. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | Преобразование из цвета CMYK в цвет ARGB с использованием Icc преобразования и пользовательского профиля. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и пользовательских профилей. |
| [toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int---java.io.InputStream-java.io.InputStream-) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и пользовательских профилей. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Преобразует RGB в CMYK с использованием пользовательских ICC профилей. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | Преобразует RGB в CMYK с использованием пользовательских ICC профилей. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | Преобразует RGB в CMYKA (с альфа-каналом) с использованием пользовательских ICC профилей. |
| [toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и пользовательских профилей. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Преобразует RGB в CMYKA (с альфа-каналом) с использованием пользовательских ICC профилей. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.imaging.Color---) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и стандартных профилей. |
| [toCmykIcc(int[] pixels)](#toCmykIcc-int---) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и стандартных профилей. |
| [toPsdCmykIcc(int[] pixels)](#toPsdCmykIcc-int---) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и стандартных профилей. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.imaging.Color-) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и стандартных профилей. |
| [toCmykIcc(int argb)](#toCmykIcc-int-) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и стандартных профилей. |
| [toPsdCmykIcc(int argb)](#toPsdCmykIcc-int-) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и стандартных профилей. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и пользовательских профилей. |
| [toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int-java.io.InputStream-java.io.InputStream-) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и пользовательских профилей. |
| [toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и пользовательских профилей. |
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Получает значение компоненты циана.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmyk | int | Цвет CMYK представлен в виде 32-битного целочисленного значения. |

**Returns:**
int — значение компонента циана.

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

//Вывод выглядит так:
//Преобразовать RGB в CMYK без использования ICC профилей.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Получает значение компоненты мадженты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmyk | int | Цвет CMYK представлен в виде 32-битного целочисленного значения. |

**Returns:**
int - Значение компонента magenta.

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

//Вывод выглядит так:
//Преобразовать RGB в CMYK без использования ICC профилей.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Получает значение желтой компоненты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmyk | int | Цвет CMYK представлен в виде 32-битного целочисленного значения. |

**Returns:**
int - Значение компонента yellow.

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

//Вывод выглядит так:
//Преобразовать RGB в CMYK без использования ICC профилей.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


Получает значение черной компоненты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmyk | int | Цвет CMYK представлен в виде 32-битного целочисленного значения. |

**Returns:**
int - Значение компонента black.

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

//Вывод выглядит так:
//Преобразовать RGB в CMYK без использования ICC профилей.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Создаёт CMYK из 32‑битных значений циана, мадженты, желтого и черного.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| циан | int | Компонент cyan. Допустимые значения от 0 до 255. |
| magenta | int | Компонент magenta. Допустимые значения от 0 до 255. |
| yellow | int | Компонент yellow. Допустимые значения от 0 до 255. |
| black | int | Компонент black. Допустимые значения от 0 до 255. |

**Returns:**
int - Цвет CMYK, представленный как 32‑битное целое значение.

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

//Вывод выглядит так:
//Преобразовать CMYK в RGB без использования ICC‑профилей.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


Преобразование из цветов ARGB в цвета CMYK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argbPixels | int[] | Цвета ARGB, представленные как 32‑битные целочисленные значения. |

**Returns:**
int[] - Цвета CMYK, представленные как 32‑битные целочисленные значения.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Преобразует ARGB в CMYK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argbPixels | int[] | Цвета RGB, представленные как 32‑битные целочисленные значения. |
| startIndex | int | Начальный индекс цвета RGB. |
| length | int | Количество пикселей RGB для преобразования. |

**Returns:**
byte[] - CMYK‑цвета, представленные в виде массива байтов.
### toCmykaBytes(int[] argbPixels, int startIndex, int length) {#toCmykaBytes-int---int-int-}
```
public static byte[] toCmykaBytes(int[] argbPixels, int startIndex, int length)
```


Преобразует ARGB в CMYKA (с прозрачностью).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argbPixels | int[] | Цвета RGB, представленные как 32‑битные целочисленные значения. |
| startIndex | int | Начальный индекс цвета RGB. |
| length | int | Количество пикселей RGB для преобразования. |

**Returns:**
byte[] - CMYK‑цвета, представленные в виде массива байтов.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


Преобразование из цвета ARGB в цвет CMYK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argbPixel | int | ARGB‑цвет, представленный в виде 32‑битного целочисленного значения. |

**Returns:**
int - Цвет CMYK, представленный как 32‑битное целое значение.
### toCmyk(Color pixel) {#toCmyk-com.aspose.imaging.Color-}
```
public static int toCmyk(Color pixel)
```


Преобразование из цвета ARGB в цвет CMYK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | ARGB‑цвет. |

**Returns:**
int - Цвет CMYK, представленный как 32‑битное целое значение.

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

//Вывод выглядит так:
//Преобразовать RGB в CMYK без использования ICC профилей.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### toCmyk(Color[] pixels) {#toCmyk-com.aspose.imaging.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


Преобразование из цветов ARGB в цвета CMYK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ARGB‑цвета. |

**Returns:**
int[] - Цвета CMYK, представленные как 32‑битные целочисленные значения.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


Преобразование из цветов CMYK в цвета ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | int[] | CMYK‑цвета, представленные в виде 32‑битных целочисленных значений. |

**Returns:**
com.aspose.imaging.Color[] - ARGB‑цвета.
### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


Преобразование из цвета CMYK в цвет ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | int | Цвет CMYK представлен в виде 32-битного целочисленного значения. |

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

//Вывод выглядит так:
//Преобразовать CMYK в RGB без использования ICC‑профилей.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


Преобразование из цветов CMYK в цвета ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | int[] | CMYK‑цвета, представленные в виде 32‑битных целочисленных значений. |

**Returns:**
int[] - ARGB‑цвета, представленные в виде 32‑битных целочисленных значений.
### toArgb32(int[] cmykPixels, boolean reuseArray) {#toArgb32-int---boolean-}
```
public static int[] toArgb32(int[] cmykPixels, boolean reuseArray)
```


Выполняет преобразование CMYK‑цветов в ARGB‑цвета и сохраняет их в тот же массив, если `reuseArray` равно `true`. В противном случае будет выделен новый массив.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | int[] | CMYK‑цвета, представленные в виде 32‑битных целочисленных значений. |
| reuseArray | boolean | если `true`, входной массив `cmykPixels` будет заполнен новыми значениями и возвращён; в противном случае будет выделен и возвращён новый массив. |

**Returns:**
int[] - Новый выделенный массив или `cmykPixels`, заполненный ARGB‑цветами, представленными в виде 32‑битных целочисленных значений.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


Преобразование из цветов CMYK в цвета ARGB с использованием Icc преобразования и стандартных профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | int[] | CMYK‑пиксели, представленные в виде 32‑битных целочисленных значений. |

**Returns:**
com.aspose.imaging.Color[] - ARGB‑цвета.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Преобразование из цветов CMYK в цвета ARGB с использованием Icc преобразования и пользовательских профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | int[] | CMYK‑цвета, представленные в виде 32‑битных целочисленных значений. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль Icc CMYK. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль Icc RGB. |

**Returns:**
com.aspose.imaging.Color[] - ARGB‑цвета.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


Преобразование из цвета CMYK в цвет ARGB с использованием Icc преобразования и стандартных профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | int | Цвет CMYK представлен в виде 32-битного целочисленного значения. |

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

// Укажите путь к пользовательским профилям ICC для RGB и CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Считайте все байты из файлов ICC в память, чтобы иметь возможность сбросить входной поток профиля перед вызовом toCmykIcc.
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

//Вывод выглядит так:
//Преобразуйте CMYK в RGB, используя профили ICC по умолчанию.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Преобразовать CMYK в RGB, используя пользовательские ICC‑профили.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Преобразование из цвета CMYK в цвет ARGB с использованием Icc преобразования и пользовательского профиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | int | Цвет CMYK представлен в виде 32-битного целочисленного значения. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль Icc CMYK. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль Icc RGB. |

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

// Укажите путь к пользовательским профилям ICC для RGB и CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Считайте все байты из файлов ICC в память, чтобы иметь возможность сбросить входной поток профиля перед вызовом toCmykIcc.
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

//Вывод выглядит так:
//Преобразуйте CMYK в RGB, используя профили ICC по умолчанию.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Преобразовать CMYK в RGB, используя пользовательские ICC‑профили.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и пользовательских профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ARGB‑цвета. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль Icc RGB. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль Icc CMYK. |

**Returns:**
int[] - Цвета CMYK, представленные как 32‑битные целочисленные значения.
### toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и пользовательских профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | ARGB‑цвета. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль Icc RGB. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль Icc CMYK. |

**Returns:**
int[] - Цвета CMYK, представленные как 32‑битные целочисленные значения.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Преобразует RGB в CMYK с использованием пользовательских ICC профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | Цвета RGB, представленные как 32‑битные целочисленные значения. |
| startIndex | int | Начальный индекс цвета RGB. |
| length | int | Количество пикселей RGB для преобразования. |
| rgbIccStream | java.io.InputStream | Поток профиля RGB. |
| cmykIccStream | java.io.InputStream | Поток профиля CMYK. |

**Returns:**
byte[] - CMYK‑цвета, представленные в виде массива байтов.
### toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


Преобразует RGB в CMYK с использованием пользовательских ICC профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | Цвета RGB, представленные как 32‑битные целочисленные значения. |
| startIndex | int | Начальный индекс цвета RGB. |
| length | int | Количество пикселей RGB для преобразования. |
| cmykBytes | byte[] | Байты Cmyk. |
| cmykOffset | int | Смещение `cmykBytes` offset. |
| rgbIccStream | java.io.InputStream | Поток профиля RGB. |
| cmykIccStream | java.io.InputStream | Поток профиля CMYK. |

**Returns:**
byte[] - CMYK‑цвета, представленные в виде массива байтов.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


Преобразует RGB в CMYKA (с альфа-каналом) с использованием пользовательских ICC профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | Цвета RGB, представленные как 32‑битные целочисленные значения. |
| startIndex | int | Начальный индекс цвета RGB. |
| length | int | Количество пикселей RGB для преобразования. |
| cmykBytes | byte[] | Байты Cmyk. |
| cmykOffset | int | Смещение `cmykBytes` offset. |
| rgbIccStream | java.io.InputStream | Поток профиля RGB. |
| cmykIccStream | java.io.InputStream | Поток профиля CMYK. |

**Returns:**
byte[] - CMYK‑цвета, представленные в виде массива байтов.
### toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Преобразование цветов ARGB в CMYK с использованием Icc‑конверсии и пользовательских профилей. Используется формат PSD CMYK, порядок байтов KCMY с инвертированными значениями каналов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | ARGB‑цвета. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль Icc RGB. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль Icc CMYK. |

**Returns:**
int[] - Цвета CMYK представлены как 32‑битные целочисленные значения в порядке байтов KCMY с инвертированными значениями каналов.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Преобразует RGB в CMYKA (с альфа-каналом) с использованием пользовательских ICC профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | Цвета RGB, представленные как 32‑битные целочисленные значения. |
| startIndex | int | Начальный индекс цвета RGB. |
| length | int | Количество пикселей RGB для преобразования. |
| rgbIccStream | java.io.InputStream | Поток профиля RGB. |
| cmykIccStream | java.io.InputStream | Поток профиля CMYK. |

**Returns:**
byte[] - CMYK‑цвета, представленные в виде массива байтов.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.imaging.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и стандартных профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ARGB‑цвета. |

**Returns:**
int[] - Цвета CMYK, представленные как 32‑битные целочисленные значения.
### toCmykIcc(int[] pixels) {#toCmykIcc-int---}
```
public static int[] toCmykIcc(int[] pixels)
```


Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и стандартных профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | ARGB‑цвета. |

**Returns:**
int[] - Цвета CMYK, представленные как 32‑битные целочисленные значения.
### toPsdCmykIcc(int[] pixels) {#toPsdCmykIcc-int---}
```
public static int[] toPsdCmykIcc(int[] pixels)
```


Преобразование цветов ARGB в CMYK с использованием Icc‑конверсии и профилей по умолчанию. Используется формат PSD CMYK, порядок байтов KCMY с инвертированными значениями каналов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | ARGB‑цвета. |

**Returns:**
int[] - Цвета CMYK представлены как 32‑битные целочисленные значения в порядке байтов KCMY с инвертированными значениями каналов.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.imaging.Color-}
```
public static int toCmykIcc(Color pixel)
```


Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и стандартных профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | ARGB‑цвет. |

**Returns:**
int - Цвет CMYK, представленный как 32‑битное целое значение.

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

// Укажите путь к ICC‑профилям RGB и CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Считайте все байты из файлов ICC в память, чтобы иметь возможность сбросить входной поток профиля перед вызовом toCmykIcc.
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

//Вывод выглядит так:
//Преобразовать RGB в CMYK, используя ICC‑профили по умолчанию.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Преобразовать RGB в CMYK, используя пользовательские ICC‑профили.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb) {#toCmykIcc-int-}
```
public static int toCmykIcc(int argb)
```


Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и стандартных профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argb | int | ARGB‑цвет. |

**Returns:**
int - Цвет CMYK, представленный как 32‑битное целое значение.
### toPsdCmykIcc(int argb) {#toPsdCmykIcc-int-}
```
public static int toPsdCmykIcc(int argb)
```


Преобразование цвета ARGB в CMYK с использованием Icc‑конверсии и профилей по умолчанию. Используется формат PSD CMYK, порядок байтов KCMY с инвертированными значениями каналов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argb | int | ARGB‑цвет. |

**Returns:**
int - Цвет CMYK, представленный как 32‑битное целочисленное значение в порядке байтов KCMY с инвертированными значениями каналов.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и пользовательских профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | ARGB‑цвет. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль Icc RGB. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль Icc CMYK. |

**Returns:**
int - Цвет CMYK, представленный как 32‑битное целое значение.

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

// Укажите путь к ICC‑профилям RGB и CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Считайте все байты из файлов ICC в память, чтобы иметь возможность сбросить входной поток профиля перед вызовом toCmykIcc.
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

//Вывод выглядит так:
//Преобразовать RGB в CMYK, используя ICC‑профили по умолчанию.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Преобразовать RGB в CMYK, используя пользовательские ICC‑профили.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)
```


Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и пользовательских профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argb | int | ARGB‑цвет. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль Icc RGB. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль Icc CMYK. |

**Returns:**
int - Цвет CMYK, представленный как 32‑битное целое значение.
### toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и пользовательских профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксель | int | ARGB‑цвет. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль Icc RGB. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль Icc CMYK. |

**Returns:**
int - Цвета CMYK, представленные как 32‑битные целочисленные значения в порядке байтов KCMY с инвертированными значениями каналов.
