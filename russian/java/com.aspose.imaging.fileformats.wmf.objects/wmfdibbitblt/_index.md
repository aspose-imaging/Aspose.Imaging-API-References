---
title: "WmfDibBitBlt"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись META_DIBBITBLT указывает передачу блока пикселей в независимом от устройства формате в соответствии с растровой операцией."
type: docs
weight: 28
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfDibBitBlt extends WmfObject
```

Запись META\_DIBBITBLT задает передачу блока пикселей в независимом от устройства формате согласно растровой операции.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfDibBitBlt()](#WmfDibBitBlt--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Получает или задает растровую операцию. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Получает или задает растровую операцию. |
| [getSrcPos()](#getSrcPos--) | Получает или задает позицию источника. |
| [setSrcPos(Point value)](#setSrcPos-com.aspose.imaging.Point-) | Получает или задает позицию источника. |
| [getHeight()](#getHeight--) | Получает или задает высоту. |
| [setHeight(short value)](#setHeight-short-) | Получает или задает высоту. |
| [getWidth()](#getWidth--) | Получает или задает ширину. |
| [setWidth(short value)](#setWidth-short-) | Получает или задает ширину. |
| [getDstPos()](#getDstPos--) | Получает или задает позицию DST. |
| [setDstPos(Point value)](#setDstPos-com.aspose.imaging.Point-) | Получает или задает позицию DST. |
| [getReserved()](#getReserved--) | Получает или задает зарезервированное значение. |
| [setReserved(int value)](#setReserved-int-) | Получает или задает зарезервированное значение. |
| [getSource()](#getSource--) | Получает или задает источник. |
| [setSource(WmfDeviceIndependentBitmap value)](#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает источник. |
### WmfDibBitBlt() {#WmfDibBitBlt--}
```
public WmfDibBitBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Получает или задает растровую операцию.

Значение: Пиксели источника, текущая кисть в контексте воспроизводящего устройства и пиксели назначения должны быть объединены для формирования нового изображения. Этот код ДОЛЖЕН быть одним из значений в перечислении Ternary Raster Operation (раздел 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Получает или задает растровую операцию.

Значение: Пиксели источника, текущая кисть в контексте воспроизводящего устройства и пиксели назначения должны быть объединены для формирования нового изображения. Этот код ДОЛЖЕН быть одним из значений в перечислении Ternary Raster Operation (раздел 2.1.1.31).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSrcPos() {#getSrcPos--}
```
public Point getSrcPos()
```


Получает или задает позицию источника.

Значение: Координаты, в логических единицах, исходного прямоугольника.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPos(Point value) {#setSrcPos-com.aspose.imaging.Point-}
```
public void setSrcPos(Point value)
```


Получает или задает позицию источника.

Значение: Координаты, в логических единицах, исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


Получает или задает высоту.

Значение: Высота, в логических единицах, исходного и целевого прямоугольников.

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


Получает или задает высоту.

Значение: Высота, в логических единицах, исходного и целевого прямоугольников.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


Получает или задает ширину.

Значение: Ширина, в логических единицах, исходного и целевого прямоугольников.

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


Получает или задает ширину.

Значение: Ширина, в логических единицах, исходного и целевого прямоугольников.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getDstPos() {#getDstPos--}
```
public Point getDstPos()
```


Получает или задает позицию DST.

Значение: Координаты, в логических единицах, верхнего левого угла целевого прямоугольника.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPos(Point value) {#setDstPos-com.aspose.imaging.Point-}
```
public void setDstPos(Point value)
```


Получает или задает позицию DST.

Значение: Координаты, в логических единицах, верхнего левого угла целевого прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public int getReserved()
```


Получает или задает зарезервированное значение.

Значение: зарезервированное значение.

**Returns:**
int
### setReserved(int value) {#setReserved-int-}
```
public void setReserved(int value)
```


Получает или задает зарезервированное значение.

Значение: зарезервированное значение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSource() {#getSource--}
```
public WmfDeviceIndependentBitmap getSource()
```


Получает или задает источник.

Значение: Объект Variable-sized DeviceIndependentBitmap (раздел 2.2.2.9), определяющий содержимое изображения. Этот объект ДОЛЖЕН быть указан, даже если растровая операция не требует источника.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSource(WmfDeviceIndependentBitmap value) {#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSource(WmfDeviceIndependentBitmap value)
```


Получает или задает источник.

Значение: Объект Variable-sized DeviceIndependentBitmap (раздел 2.2.2.9), определяющий содержимое изображения. Этот объект ДОЛЖЕН быть указан, даже если растровая операция не требует источника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

