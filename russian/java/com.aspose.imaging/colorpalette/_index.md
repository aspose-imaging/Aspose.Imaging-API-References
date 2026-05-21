---
title: "ColorPalette"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Определяет массив цветов, составляющих цветовую палитру."
type: docs
weight: 28
url: /ru/java/com.aspose.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IColorPalette](../../com.aspose.imaging/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Определяет массив цветов, составляющих цветовую палитру. Цвета — 32‑битные ARGB‑цвета. Не наследуемый.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Инициализирует новый экземпляр класса `ColorPalette`. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Инициализирует новый экземпляр класса `ColorPalette`, и IsCompactPalette равно false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.imaging.Color---boolean-) | Инициализирует новый экземпляр класса `ColorPalette`. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.imaging.Color---) | Инициализирует новый экземпляр класса `ColorPalette`, и IsCompactPalette равно false. |
## Методы

| Метод | Описание |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Получает количество записей. |
| [getArgb32Entries()](#getArgb32Entries--) | Получает массив 32‑битных ARGB‑структур. |
| [getEntries()](#getEntries--) | Получает массив структур `com.aspose.imaging.Color`. |
| [isCompactPalette()](#isCompactPalette--) | Получает или задает значение, указывающее, используется ли компактная палитра. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.imaging.IColorPalette-boolean-) | Копирует палитру. |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.imaging.IColorPalette-) | Копирует палитру. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Получает индекс ближайшего цвета. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.imaging.Color-) | Получает индекс ближайшего цвета. |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Получает 32‑битный ARGB‑цвет палитры по индексу. |
| [getColor(int index)](#getColor-int-) | Получает цвет палитры по индексу. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


Инициализирует новый экземпляр класса `ColorPalette`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argb32Entries | int[] | 32‑битные записи цветовой палитры ARGB. |
| isCompactPalette | boolean | Указывает, является ли палитра компактной. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Инициализирует новый экземпляр класса `ColorPalette`, и IsCompactPalette равно false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argb32Entries | int[] | 32‑битные записи цветовой палитры ARGB. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.imaging.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Инициализирует новый экземпляр класса `ColorPalette`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Записи цветовой палитры. |
| isCompactPalette | boolean | Указывает, является ли палитра компактной. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.imaging.Color---}
```
public ColorPalette(Color[] entries)
```


Инициализирует новый экземпляр класса `ColorPalette`, и IsCompactPalette равно false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Записи цветовой палитры. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Получает количество записей.

**Returns:**
int - Количество записей.
### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Получает массив 32‑битных ARGB‑структур.

**Returns:**
int[] - Записи. Копия массива 32‑битных значений ARGB, составляющих эту [ColorPalette](../../com.aspose.imaging/colorpalette).
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Получает массив структур `com.aspose.imaging.Color`.

**Returns:**
com.aspose.imaging.Color[] - Записи. Копия массива структур [Color](../../com.aspose.imaging/color), составляющих эту [ColorPalette](../../com.aspose.imaging/colorpalette).
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Получает или задает значение, указывающее, используется ли компактная палитра.

**Returns:**
boolean — `true`, если используется компактная палитра; иначе `false`.

Компактная палитра означает, что изображение будет содержать только указанные записи палитры, если это возможно, другими словами изображение будет более компактным и займет меньше места; в противном случае будет 2^BitsPerPixel записей, и изображение зарезервирует больше места для всех возможных записей палитры. Установка этого значения в true и изменение записей палитры могут привести к потере производительности, поскольку может происходить перемещение данных, поэтому используйте это с осторожностью.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Копирует палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Цветовая палитра. |
| useCompactPalette | boolean | Указывает, является ли палитра компактной. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.imaging.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Копирует палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Цветовая палитра. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public int getNearestColorIndex(int argb32Color)
```


Получает индекс ближайшего цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argb32Color | int | 32‑битный цвет ARGB. |

**Returns:**
int — индекс ближайшего цвета.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.imaging.Color-}
```
public int getNearestColorIndex(Color color)
```


Получает индекс ближайшего цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Цвет. |

**Returns:**
int — индекс ближайшего цвета.
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
```


Получает 32‑битный ARGB‑цвет палитры по индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | 32‑битный индекс цвета палитры ARGB. |

**Returns:**
int — запись цветовой палитры, указанная `index`.
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
```


Получает цвет палитры по индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс цвета палитры. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color palette entry specified by the `index`.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
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
