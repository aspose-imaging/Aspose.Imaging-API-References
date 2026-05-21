---
title: "WmfStretchBlt"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись META_STRETCHBLT определяет передачу блока пикселей в соответствии с растровой операцией с возможным расширением или сжатием."
type: docs
weight: 93
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfStretchBlt extends WmfObject
```

Запись META\_STRETCHBLT указывает передачу блока пикселей согласно растровой операции, с возможным расширением или сжатием.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfStretchBlt()](#WmfStretchBlt--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Получает или задает растровую операцию. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Получает или задает растровую операцию. |
| [getSrcHeight()](#getSrcHeight--) | Получает или задает высоту источника. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Получает или задает высоту источника. |
| [getSrcWidth()](#getSrcWidth--) | Получает или задает ширину источника. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Получает или задает ширину источника. |
| [getSrcPosition()](#getSrcPosition--) | Получает или задает позицию источника. |
| [setSrcPosition(Point value)](#setSrcPosition-com.aspose.imaging.Point-) | Получает или задает позицию источника. |
| [getDestHeight()](#getDestHeight--) | Получает или задает высоту назначения. |
| [setDestHeight(short value)](#setDestHeight-short-) | Получает или задает высоту назначения. |
| [getDestWidth()](#getDestWidth--) | Получает или задает ширину назначения. |
| [setDestWidth(short value)](#setDestWidth-short-) | Получает или задает ширину назначения. |
| [getDstPosition()](#getDstPosition--) | Получает или задает позицию DST. |
| [setDstPosition(Point value)](#setDstPosition-com.aspose.imaging.Point-) | Получает или задает позицию DST. |
| [getReserved()](#getReserved--) | Получает или задает зарезервированное значение. |
| [setReserved(short value)](#setReserved-short-) | Получает или задает зарезервированное значение. |
| [getBitmap()](#getBitmap--) | Получает или задает растровое изображение. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Получает или задает растровое изображение. |
### WmfStretchBlt() {#WmfStretchBlt--}
```
public WmfStretchBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Получает или задает растровую операцию.

Значение: Исходные пиксели, текущая кисть в контексте воспроизведения устройства и пиксели назначения должны быть объединены для формирования нового изображения. Этот код ДОЛЖЕН быть одним из значений в перечислении Ternary Raster Operation.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Получает или задает растровую операцию.

Значение: Исходные пиксели, текущая кисть в контексте воспроизведения устройства и пиксели назначения должны быть объединены для формирования нового изображения. Этот код ДОЛЖЕН быть одним из значений в перечислении Ternary Raster Operation.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSrcHeight() {#getSrcHeight--}
```
public short getSrcHeight()
```


Получает или задает высоту источника.

Значение: Высота, в логических единицах, исходного прямоугольника.

**Returns:**
short
### setSrcHeight(short value) {#setSrcHeight-short-}
```
public void setSrcHeight(short value)
```


Получает или задает высоту источника.

Значение: Высота, в логических единицах, исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getSrcWidth() {#getSrcWidth--}
```
public short getSrcWidth()
```


Получает или задает ширину источника.

Значение: Ширина исходного прямоугольника в логических единицах.

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Получает или задает ширину источника.

Значение: Ширина исходного прямоугольника в логических единицах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getSrcPosition() {#getSrcPosition--}
```
public Point getSrcPosition()
```


Получает или задает позицию источника.

Значение: Позиция источника.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPosition(Point value) {#setSrcPosition-com.aspose.imaging.Point-}
```
public void setSrcPosition(Point value)
```


Получает или задает позицию источника.

Значение: Позиция источника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDestHeight() {#getDestHeight--}
```
public short getDestHeight()
```


Получает или задает высоту назначения.

Значение: Высота, в логических единицах, прямоугольника назначения.

**Returns:**
short
### setDestHeight(short value) {#setDestHeight-short-}
```
public void setDestHeight(short value)
```


Получает или задает высоту назначения.

Значение: Высота, в логических единицах, прямоугольника назначения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getDestWidth() {#getDestWidth--}
```
public short getDestWidth()
```


Получает или задает ширину назначения.

Значение: Ширина, в логических единицах, прямоугольника назначения.

**Returns:**
short
### setDestWidth(short value) {#setDestWidth-short-}
```
public void setDestWidth(short value)
```


Получает или задает ширину назначения.

Значение: Ширина, в логических единицах, прямоугольника назначения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getDstPosition() {#getDstPosition--}
```
public Point getDstPosition()
```


Получает или задает позицию DST.

Значение: Позиция DST.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPosition(Point value) {#setDstPosition-com.aspose.imaging.Point-}
```
public void setDstPosition(Point value)
```


Получает или задает позицию DST.

Значение: Позиция DST.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Получает или задает зарезервированное значение.

Значение: Зарезервировано. Это поле ДОЛЖНО игнорироваться.

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Получает или задает зарезервированное значение.

Значение: Зарезервировано. Это поле ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Получает или задает растровое изображение.

Значение: Битовая карта.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Получает или задает растровое изображение.

Значение: Битовая карта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

