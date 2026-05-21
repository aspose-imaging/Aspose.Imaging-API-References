---
title: "ClaheFilterOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Предоставляет параметры для настройки фильтра Contrast-Limited Adaptive Histogram Equalization CLAHE."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class ClaheFilterOptions extends FilterOptionsBase
```

Предоставляет параметры для настройки фильтра Contrast-Limited Adaptive Histogram Equalization (CLAHE).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ClaheFilterOptions()](#ClaheFilterOptions--) |  |
| [ClaheFilterOptions(boolean isGrayscale)](#ClaheFilterOptions-boolean-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)](#ClaheFilterOptions-boolean-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)](#ClaheFilterOptions-boolean-int-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)](#ClaheFilterOptions-boolean-int-int-double-) | Инициализирует новый экземпляр класса [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) с указанными параметрами. |
## Методы

| Метод | Описание |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Возвращает значение, указывающее, работает ли фильтр в режиме градаций серого. |
| [getTilesNumberHorizontal()](#getTilesNumberHorizontal--) | Возвращает количество плиток в горизонтальном направлении. |
| [getTilesNumberVertical()](#getTilesNumberVertical--) | Возвращает количество плиток в вертикальном направлении. |
| [getClipLimit()](#getClipLimit--) | Возвращает порог ограничения контраста. |
### ClaheFilterOptions() {#ClaheFilterOptions--}
```
public ClaheFilterOptions()
```


### ClaheFilterOptions(boolean isGrayscale) {#ClaheFilterOptions-boolean-}
```
public ClaheFilterOptions(boolean isGrayscale)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isGrayscale | boolean |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal) {#ClaheFilterOptions-boolean-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical) {#ClaheFilterOptions-boolean-int-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |
| tilesNumberVertical | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit) {#ClaheFilterOptions-boolean-int-int-double-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)
```


Инициализирует новый экземпляр класса [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) с указанными параметрами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isGrayscale | boolean | Указывает, должен ли фильтр работать в режиме градаций серого. |
| tilesNumberHorizontal | int | Количество плиток по горизонтали. По умолчанию 8. |
| tilesNumberVertical | int | Количество плиток по вертикали. По умолчанию 8. |
| clipLimit | double | Порог ограничения контраста. По умолчанию 4.0. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Возвращает значение, указывающее, работает ли фильтр в режиме градаций серого.

**Returns:**
boolean — значение, указывающее, работает ли фильтр в режиме градаций серого.
### getTilesNumberHorizontal() {#getTilesNumberHorizontal--}
```
public final int getTilesNumberHorizontal()
```


Возвращает количество плиток в горизонтальном направлении. Определяет, на сколько регионов изображение делится по горизонтали для локального выравнивания контраста.

**Returns:**
int — количество плиток в горизонтальном направлении.
### getTilesNumberVertical() {#getTilesNumberVertical--}
```
public final int getTilesNumberVertical()
```


Возвращает количество плиток в вертикальном направлении. Определяет, на сколько регионов изображение делится по вертикали для локального выравнивания контраста.

**Returns:**
int — количество плиток в вертикальном направлении.
### getClipLimit() {#getClipLimit--}
```
public final double getClipLimit()
```


Возвращает порог ограничения контраста. Более высокие значения позволяют увеличить контраст; более низкие ограничивают усиление, чтобы предотвратить усиление шума.

**Returns:**
double — порог ограничения контраста.
