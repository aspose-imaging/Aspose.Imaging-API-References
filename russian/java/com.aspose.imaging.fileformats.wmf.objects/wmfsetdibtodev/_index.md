---
title: "WmfSetDibToDev"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись META_SETDIBTODEV устанавливает блок пикселей в контексте устройства воспроизведения, используя независимые от устройства данные о цвете."
type: docs
weight: 75
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetdibtodev/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetDibToDev extends WmfObject
```

Запись META\\_SETDIBTODEV устанавливает блок пикселей в контексте устройства воспроизведения, используя независимые от устройства данные о цвете. Источник данных о цвете — DIB.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfSetDibToDev()](#WmfSetDibToDev--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getColorUsage()](#getColorUsage--) | Получает или задает использование цвета. |
| [setColorUsage(int value)](#setColorUsage-int-) | Получает или задает использование цвета. |
| [getScanCount()](#getScanCount--) | Получает или задает количество сканов. |
| [setScanCount(int value)](#setScanCount-int-) | Получает или задает количество сканов. |
| [getStartScan()](#getStartScan--) | Получает или задает начальный скан. |
| [setStartScan(int value)](#setStartScan-int-) | Получает или задает начальный скан. |
| [getDibPos()](#getDibPos--) | Получает или задает позицию dib. |
| [setDibPos(Point value)](#setDibPos-com.aspose.imaging.Point-) | Получает или задает позицию dib. |
| [getHeight()](#getHeight--) | Получает или задает высоту. |
| [setHeight(int value)](#setHeight-int-) | Получает или задает высоту. |
| [getWidth()](#getWidth--) | Получает или задает ширину. |
| [setWidth(int value)](#setWidth-int-) | Получает или задает ширину. |
| [getDestPos()](#getDestPos--) | Получает или задает позицию назначения. |
| [setDestPos(Point value)](#setDestPos-com.aspose.imaging.Point-) | Получает или задает позицию назначения. |
| [getDib()](#getDib--) | Получает или задает dib. |
| [setDib(WmfDeviceIndependentBitmap value)](#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает dib. |
### WmfSetDibToDev() {#WmfSetDibToDev--}
```
public WmfSetDibToDev()
```


### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Получает или задает использование цвета.

Значение: Поле Colors DIB содержит явные значения RGB или индексы в палитре. Оно ДОЛЖНО быть одним из значений в перечислении `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` (раздел 2.1.1.6).

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Получает или задает использование цвета.

Значение: Поле Colors DIB содержит явные значения RGB или индексы в палитре. Оно ДОЛЖНО быть одним из значений в перечислении `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` (раздел 2.1.1.6).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getScanCount() {#getScanCount--}
```
public int getScanCount()
```


Получает или задает количество сканов.

Значение: Количество строк сканирования в источнике.

**Returns:**
int
### setScanCount(int value) {#setScanCount-int-}
```
public void setScanCount(int value)
```


Получает или задает количество сканов.

Значение: Количество строк сканирования в источнике.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getStartScan() {#getStartScan--}
```
public int getStartScan()
```


Получает или задает начальный скан.

Значение: Начальная строка сканирования в источнике.

**Returns:**
int
### setStartScan(int value) {#setStartScan-int-}
```
public void setStartScan(int value)
```


Получает или задает начальный скан.

Значение: Начальная строка сканирования в источнике.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDibPos() {#getDibPos--}
```
public Point getDibPos()
```


Получает или задает позицию dib.

Значение: Координаты, в логических единицах, исходного прямоугольника.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDibPos(Point value) {#setDibPos-com.aspose.imaging.Point-}
```
public void setDibPos(Point value)
```


Получает или задает позицию dib.

Значение: Координаты, в логических единицах, исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает или задает высоту.

Значение: Высота, в логических единицах, исходного и целевого прямоугольников.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Получает или задает высоту.

Значение: Высота, в логических единицах, исходного и целевого прямоугольников.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает или задает ширину.

Значение: Ширина, в логических единицах, исходного и целевого прямоугольников.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Получает или задает ширину.

Значение: Ширина, в логических единицах, исходного и целевого прямоугольников.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDestPos() {#getDestPos--}
```
public Point getDestPos()
```


Получает или задает позицию назначения.

Значение: Координаты, в логических единицах, верхнего левого угла целевого прямоугольника.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDestPos(Point value) {#setDestPos-com.aspose.imaging.Point-}
```
public void setDestPos(Point value)
```


Получает или задает позицию назначения.

Значение: Координаты, в логических единицах, верхнего левого угла целевого прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDib() {#getDib--}
```
public WmfDeviceIndependentBitmap getDib()
```


Получает или задает dib.

Значение: Координата y, в логических единицах, верхнего левого угла прямоугольника назначения.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setDib(WmfDeviceIndependentBitmap value) {#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setDib(WmfDeviceIndependentBitmap value)
```


Получает или задает dib.

Значение: Координата y, в логических единицах, верхнего левого угла прямоугольника назначения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

