---
title: "CmykColor"
second_title: "Справочник API Aspose.Imaging для Java"
description: "CMYK‑цвет пикселя."
type: docs
weight: 18
url: /ru/java/com.aspose.imaging/cmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

CMYK‑цвет пикселя.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getEmpty()](#getEmpty--) | Возвращает пустой. |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Создаёт структуру `CmykColor` из 32‑битных значений cyan, magenta, yellow и black. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Преобразование 32‑битного цвета ARGB в CMYKColor. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.imaging.CmykColor---) | Преобразование CMYKColor в Color с использованием ICC‑преобразования и профилей по умолчанию. |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.imaging.CmykColor---) | Преобразование CMYKColor в 32‑битный цвет ARGB с использованием ICC‑преобразования и профилей по умолчанию. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Преобразование 32‑битного ARGB в CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.imaging.CmykColor-) | Преобразование CMYKColor в Color. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.imaging.CmykColor---) | Преобразование CMYKColor в Color с использованием ICC‑преобразования и профилей по умолчанию. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.imaging.CmykColor-) | Преобразование CMYKColor в Color с использованием ICC‑преобразования и профилей по умолчанию. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-) | Преобразование CMYKColor в Color с использованием ICC‑преобразования. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-) | Преобразование CMYKColor в Color с использованием ICC‑преобразования. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-) |  |
| [getC()](#getC--) | Получает значение компонента cyan этой структуры `com.com.aspose.imaging.Color`. |
| [getM()](#getM--) | Получает значение компонента magenta этой структуры `com.com.aspose.imaging.Color`. |
| [getY()](#getY--) | Получает значение компонента yellow этой структуры `com.com.aspose.imaging.Color`. |
| [getK()](#getK--) | Получает значение компонента black этой структуры `com.com.aspose.imaging.Color`. |
| [isEmpty()](#isEmpty--) | Возвращает значение, указывающее, инициализирована ли эта структура `com.com.aspose.imaging.Color`. |
| [hashCode()](#hashCode--) | Получить хеш-код. |
| [toValue()](#toValue--) | Получить значение. |
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


Возвращает пустой.

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Создает структуру `CmykColor` из 32‑битных значений cyan, magenta, yellow и black. Этот метод устарел. Пожалуйста, используйте более эффективный CmykColorHelper\#fromComponents(int, int, int, int).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| циан | int | Компонент cyan. Допустимые значения от 0 до 255. |
| magenta | int | Компонент magenta. Допустимые значения от 0 до 255. |
| yellow | int | Компонент yellow. Допустимые значения от 0 до 255. |
| black | int | Компонент black. Допустимые значения от 0 до 255. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The `CmykColor`.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


Преобразование из 32‑битного цвета ARGB в CMYKColor. Этот метод устарел. Пожалуйста, используйте более эффективный `CmykColorHelper.toCmyk(int[])`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argbPixels | int[] | Пиксели в формате 32‑битного ARGB. |

**Returns:**
com.aspose.imaging.CmykColor[] - [CmykColor](../../com.aspose.imaging/cmykcolor)
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.imaging.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


Преобразование из CMYKColor в Color с использованием ICC‑преобразования и профилей по умолчанию. Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.toArgb(int)](../../com.aspose.imaging/cmykcolorhelper\#toArgb-int-)\}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |

**Returns:**
com.aspose.imaging.Color[] — массив ARGB‑цветов.
### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.imaging.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


Преобразование из CMYKColor в 32‑битный ARGB Color с использованием ICC‑преобразования и профилей по умолчанию. Этот метод устарел. Пожалуйста, используйте более эффективный `CmykColorHelper.toArgb32(int[])`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |

**Returns:**
int[] — массив 32‑битных ARGB‑цветов.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


Преобразование из 32‑битного ARGB в CMYKColor. Этот метод устарел. Пожалуйста, используйте более эффективный `CmykColorHelper.toCmyk(int)`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argbPixel | int | Пиксель в формате 32‑битного ARGB. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The [CmykColor](../../com.aspose.imaging/cmykcolor).
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.imaging.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


Преобразование из CMYKColor в Color. Этот метод устарел. Пожалуйста, используйте более эффективный `CmykColorHelper.toArgb(int)`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.imaging.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


Преобразование из CMYKColor в Color с использованием ICC‑преобразования и профилей по умолчанию. Этот метод устарел. Пожалуйста, используйте более эффективный CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |

**Returns:**
com.aspose.imaging.Color[] — `com.com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.imaging.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


Преобразование из CMYKColor в Color с использованием ICC‑преобразования и профилей по умолчанию. Этот метод устарел. Пожалуйста, используйте более эффективный `CmykColorHelper.toArgbIcc(int)`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Пиксель типа CMYKColor в формате CMYK. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Преобразование из CMYKColor в Color с использованием ICC‑преобразования. Этот метод устарел. Пожалуйста, используйте более эффективный `CmykColorHelper.toArgbIcc(int[], InputStream, InputStream)`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль icc cmyk. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль icc rgb. |

**Returns:**
com.aspose.imaging.Color[] — `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Преобразование из CMYKColor в Color с использованием ICC‑преобразования. Этот метод устарел. Пожалуйста, используйте более эффективный `CmykColorHelper.toArgbIcc(int, Stream, Stream)`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Пиксель типа CMYKColor в формате CMYK. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль icc cmyk. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль icc rgb. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

**Returns:**
boolean
### getC() {#getC--}
```
public byte getC()
```


Получает значение компонента cyan этой структуры `com.com.aspose.imaging.Color`.

**Returns:**
byte — значение компоненты cyan этой `com.com.aspose.imaging.Color`.
### getM() {#getM--}
```
public byte getM()
```


Получает значение компонента magenta этой структуры `com.com.aspose.imaging.Color`.

**Returns:**
byte — значение компоненты magenta этой `com.com.aspose.imaging.Color`.
### getY() {#getY--}
```
public byte getY()
```


Получает значение компонента yellow этой структуры `com.com.aspose.imaging.Color`.

**Returns:**
byte — значение компоненты yellow этой `com.com.aspose.imaging.Color`.
### getK() {#getK--}
```
public byte getK()
```


Получает значение компонента black этой структуры `com.com.aspose.imaging.Color`.

Значение: значение компоненты black этой `com.com.aspose.imaging.Color`.

**Returns:**
byte
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Возвращает значение, указывающее, инициализирована ли эта структура `com.com.aspose.imaging.Color`.

**Returns:**
boolean - Возвращает true, если этот цвет не инициализирован; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получить хеш-код.

**Returns:**
int - Тип `int`.
### toValue() {#toValue--}
```
public long toValue()
```


Получить значение.

**Returns:**
long - Длинное значение CMYK.
### CloneTo(CmykColor that) {#CloneTo-com.aspose.imaging.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
