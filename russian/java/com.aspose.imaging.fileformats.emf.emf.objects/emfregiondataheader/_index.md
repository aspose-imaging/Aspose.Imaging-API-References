---
title: "EmfRegionDataHeader"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект RegionDataHeader описывает свойства объекта RegionData."
type: docs
weight: 34
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionDataHeader extends EmfObject
```

Объект RegionDataHeader описывает свойства объекта RegionData.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getSize()](#getSize--) | Получает 32‑битное беззнаковое целое число, которое указывает размер этого объекта в байтах. |
| [setSize(int value)](#setSize-int-) | Задает 32‑битное беззнаковое целое число, которое указывает размер этого объекта в байтах. |
| [getType()](#getType--) | Получает 32‑битное беззнаковое целое число, которое указывает тип региона. |
| [setType(int value)](#setType-int-) | Задает 32‑битное беззнаковое целое число, которое указывает тип региона. |
| [getCountRects()](#getCountRects--) | Получает 32‑битное беззнаковое целое число, которое указывает количество прямоугольников в этом регионе. |
| [setCountRects(int value)](#setCountRects-int-) | Устанавливает 32-битное беззнаковое целое, которое определяет количество прямоугольников в этой области. |
| [getRgnSize()](#getRgnSize--) | Получает 32-битное беззнаковое целое, которое определяет размер буфера прямоугольников в байтах. |
| [setRgnSize(int value)](#setRgnSize-int-) | Устанавливает 32-битное беззнаковое целое, которое определяет размер буфера прямоугольников в байтах. |
| [getBounds()](#getBounds--) | Получает 128-битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет границы области. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Устанавливает 128-битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет границы области. |
### EmfRegionDataHeader() {#EmfRegionDataHeader--}
```
public EmfRegionDataHeader()
```


### getSize() {#getSize--}
```
public int getSize()
```


Получает 32-битное беззнаковое целое, которое определяет размер этого объекта в байтах. Оно ДОЛЖНО быть 0x00000020.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Устанавливает 32-битное беззнаковое целое, которое определяет размер этого объекта в байтах. Оно ДОЛЖНО быть 0x00000020.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public int getType()
```


Получает 32-битное беззнаковое целое, которое определяет тип области. Оно ДОЛЖНО быть RDH\_RECTANGLES (0x00000001).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Устанавливает 32-битное беззнаковое целое, которое определяет тип области. Оно ДОЛЖНО быть RDH\_RECTANGLES (0x00000001).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCountRects() {#getCountRects--}
```
public int getCountRects()
```


Получает 32‑битное беззнаковое целое число, которое указывает количество прямоугольников в этом регионе.

**Returns:**
int
### setCountRects(int value) {#setCountRects-int-}
```
public void setCountRects(int value)
```


Устанавливает 32-битное беззнаковое целое, которое определяет количество прямоугольников в этой области.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRgnSize() {#getRgnSize--}
```
public int getRgnSize()
```


Получает 32-битное беззнаковое целое, которое определяет размер буфера прямоугольников в байтах.

**Returns:**
int
### setRgnSize(int value) {#setRgnSize-int-}
```
public void setRgnSize(int value)
```


Устанавливает 32-битное беззнаковое целое, которое определяет размер буфера прямоугольников в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает 128-битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет границы области.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Устанавливает 128-битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет границы области.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

