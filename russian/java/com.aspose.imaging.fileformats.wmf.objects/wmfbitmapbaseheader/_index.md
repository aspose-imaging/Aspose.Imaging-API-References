---
title: "WmfBitmapBaseHeader"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Базовый класс заголовка растрового изображения."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public abstract class WmfBitmapBaseHeader extends MetaObject
```

Базовый класс заголовка растрового изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfBitmapBaseHeader()](#WmfBitmapBaseHeader--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Получает или задает 32-битное беззнаковое целое, определяющее размер этого объекта в байтах. |
| [setHeaderSize(int value)](#setHeaderSize-int-) | Получает или задает 32-битное беззнаковое целое, определяющее размер этого объекта в байтах. |
| [getPlanes()](#getPlanes--) | Получает или задает 16-битное беззнаковое целое, определяющее количество `planes` для целевого устройства. |
| [setPlanes(short value)](#setPlanes-short-) | Получает или задает 16-битное беззнаковое целое, определяющее количество `planes` для целевого устройства. |
| [getBitCount()](#getBitCount--) | Получает или задает 16-битное беззнаковое целое, определяющее формат каждого пикселя и максимальное количество цветов в DIB. |
| [setBitCount(short value)](#setBitCount-short-) | Получает или задает 16-битное беззнаковое целое, определяющее формат каждого пикселя и максимальное количество цветов в DIB. |
### WmfBitmapBaseHeader() {#WmfBitmapBaseHeader--}
```
public WmfBitmapBaseHeader()
```


### getHeaderSize() {#getHeaderSize--}
```
public int getHeaderSize()
```


Получает или задает 32-битное беззнаковое целое, определяющее размер этого объекта в байтах.

**Returns:**
int
### setHeaderSize(int value) {#setHeaderSize-int-}
```
public void setHeaderSize(int value)
```


Получает или задает 32-битное беззнаковое целое, определяющее размер этого объекта в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | 16-битное беззнаковое целое, определяющее количество `planes` для целевого устройства. Это значение ДОЛЖНО быть 0x0001. |

### getPlanes() {#getPlanes--}
```
public short getPlanes()
```


Получает или задает 16-битное беззнаковое целое, определяющее количество `planes` для целевого устройства. Это значение ДОЛЖНО быть 0x0001.

**Returns:**
short — 16-битное беззнаковое целое, определяющее количество `planes` для целевого устройства.
### setPlanes(short value) {#setPlanes-short-}
```
public void setPlanes(short value)
```


Получает или задает 16-битное беззнаковое целое, определяющее количество `planes` для целевого устройства. Это значение ДОЛЖНО быть 0x0001.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short | 16-битное беззнаковое целое, определяющее количество `planes` для целевого устройства. Это значение ДОЛЖНО быть \* 0x0001. |

### getBitCount() {#getBitCount--}
```
public short getBitCount()
```


Получает или задает 16-битное беззнаковое целое, определяющее формат каждого пикселя и максимальное количество цветов в DIB. Это значение ДОЛЖНО быть в перечислении `BitCount` (раздел 2.1.1.3).

**Returns:**
short — 16-битное беззнаковое целое, определяющее формат каждого пикселя и максимальное количество цветов в DIB.
### setBitCount(short value) {#setBitCount-short-}
```
public void setBitCount(short value)
```


Получает или задает 16-битное беззнаковое целое, определяющее формат каждого пикселя и максимальное количество цветов в DIB. Это значение ДОЛЖНО быть в перечислении `BitCount` (раздел 2.1.1.3).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short | 16-битное беззнаковое целое, определяющее формат каждого пикселя и максимальное количество цветов в DIB. |

