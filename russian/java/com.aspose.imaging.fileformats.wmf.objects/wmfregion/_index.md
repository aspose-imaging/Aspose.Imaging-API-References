---
title: "WmfRegion"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект Region определяет потенциально неректильную форму, задаваемую     массивом сканлайнов."
type: docs
weight: 62
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfRegion extends MetaObject
```

Объект Region определяет потенциально неректильную форму, заданную массивом сканирующих линий.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfRegion()](#WmfRegion--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getNextInChain()](#getNextInChain--) | Получает или задает следующий элемент в цепочке. |
| [setNextInChain(short value)](#setNextInChain-short-) | Получает или задает следующий элемент в цепочке. |
| [getObjectType()](#getObjectType--) | Получает или задает тип объекта. |
| [setObjectType(short value)](#setObjectType-short-) | Получает или задает тип объекта. |
| [getObjectCount()](#getObjectCount--) | Получает или задает количество объектов. |
| [setObjectCount(int value)](#setObjectCount-int-) | Получает или задает количество объектов. |
| [getRegionSize()](#getRegionSize--) | Получает или задает размер области. |
| [setRegionSize(short value)](#setRegionSize-short-) | Получает или задает размер области. |
| [getScanCount()](#getScanCount--) | Получает или задает количество сканов. |
| [setScanCount(short value)](#setScanCount-short-) | Получает или задает количество сканов. |
| [getMaxScan()](#getMaxScan--) | Получает или задает максимальный скан. |
| [setMaxScan(short value)](#setMaxScan-short-) | Получает или задает максимальный скан. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Получает или задает ограничивающий прямоугольник. |
| [setBoundingRectangle(Rectangle value)](#setBoundingRectangle-com.aspose.imaging.Rectangle-) | Получает или задает ограничивающий прямоугольник. |
| [getAScans()](#getAScans--) | Получает или задает сканы. |
| [setAScans(WmfScanObject[] value)](#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---) | Получает или задает сканы. |
### WmfRegion() {#WmfRegion--}
```
public WmfRegion()
```


### getNextInChain() {#getNextInChain--}
```
public short getNextInChain()
```


Получает или задает следующий элемент в цепочке.

Значение: Значение, которое ДОЛЖНО быть проигнорировано.

**Returns:**
short
### setNextInChain(short value) {#setNextInChain-short-}
```
public void setNextInChain(short value)
```


Получает или задает следующий элемент в цепочке.

Значение: Значение, которое ДОЛЖНО быть проигнорировано.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getObjectType() {#getObjectType--}
```
public short getObjectType()
```


Получает или задает тип объекта.

Значение: Идентификатор региона. Он ДОЛЖЕН быть 0x0006.

**Returns:**
short
### setObjectType(short value) {#setObjectType-short-}
```
public void setObjectType(short value)
```


Получает или задает тип объекта.

Значение: Идентификатор региона. Он ДОЛЖЕН быть 0x0006.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getObjectCount() {#getObjectCount--}
```
public int getObjectCount()
```


Получает или задает количество объектов.

Значение: Значение, которое ДОЛЖНО быть проигнорировано.

**Returns:**
int
### setObjectCount(int value) {#setObjectCount-int-}
```
public void setObjectCount(int value)
```


Получает или задает количество объектов.

Значение: Значение, которое ДОЛЖНО быть проигнорировано.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRegionSize() {#getRegionSize--}
```
public short getRegionSize()
```


Получает или задает размер области.

Значение: Размер региона в байтах плюс размер aScans в байтах.

**Returns:**
short
### setRegionSize(short value) {#setRegionSize-short-}
```
public void setRegionSize(short value)
```


Получает или задает размер области.

Значение: Размер региона в байтах плюс размер aScans в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getScanCount() {#getScanCount--}
```
public short getScanCount()
```


Получает или задает количество сканов.

Значение: Количество строк сканирования, составляющих регион.

**Returns:**
short
### setScanCount(short value) {#setScanCount-short-}
```
public void setScanCount(short value)
```


Получает или задает количество сканов.

Значение: Количество строк сканирования, составляющих регион.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getMaxScan() {#getMaxScan--}
```
public short getMaxScan()
```


Получает или задает максимальный скан.

Значение: Максимальное количество точек в любой отдельной сканировке в этом регионе.

**Returns:**
short
### setMaxScan(short value) {#setMaxScan-short-}
```
public void setMaxScan(short value)
```


Получает или задает максимальный скан.

Значение: Максимальное количество точек в любой отдельной сканировке в этом регионе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Получает или задает ограничивающий прямоугольник.

Значение: Объект Rect (раздел 2.2.2.18), определяющий ограничивающий прямоугольник.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBoundingRectangle(Rectangle value) {#setBoundingRectangle-com.aspose.imaging.Rectangle-}
```
public void setBoundingRectangle(Rectangle value)
```


Получает или задает ограничивающий прямоугольник.

Значение: Объект Rect (раздел 2.2.2.18), определяющий ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAScans() {#getAScans--}
```
public WmfScanObject[] getAScans()
```


Получает или задает сканы.

Значение: Массив объектов Scan (раздел 2.2.2.21), определяющих строки сканирования в регионе.

**Returns:**
com.aspose.imaging.fileformats.wmf.objects.WmfScanObject[]
### setAScans(WmfScanObject[] value) {#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---}
```
public void setAScans(WmfScanObject[] value)
```


Получает или задает сканы.

Значение: Массив объектов Scan (раздел 2.2.2.21), определяющих строки сканирования в регионе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfScanObject\[\]](../../com.aspose.imaging.fileformats.wmf.objects/wmfscanobject) |  |

