---
title: "WmfScanObject"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект Scan указывает коллекцию сканирующих линий."
type: docs
weight: 69
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfscanobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfScanObject extends MetaObject
```

Объект Scan указывает коллекцию сканирующих линий.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfScanObject()](#WmfScanObject--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Получает или задает количество. |
| [setCount(int value)](#setCount-int-) | Получает или задает количество. |
| [getTop()](#getTop--) | Получает или задает верхнюю границу. |
| [setTop(int value)](#setTop-int-) | Получает или задает верхнюю границу. |
| [getBottom()](#getBottom--) | Получает или задает нижнюю границу. |
| [setBottom(int value)](#setBottom-int-) | Получает или задает нижнюю границу. |
| [getScanLines()](#getScanLines--) | Получает или задает строки сканирования. |
| [setScanLines(Point[] value)](#setScanLines-com.aspose.imaging.Point---) | Получает или задает строки сканирования. |
| [getCount2()](#getCount2--) | Получает или задает count2. |
| [setCount2(int value)](#setCount2-int-) | Получает или задает count2. |
### WmfScanObject() {#WmfScanObject--}
```
public WmfScanObject()
```


### getCount() {#getCount--}
```
public int getCount()
```


Получает или задает количество.

Значение: Количество горизонтальных (по оси x) координат в массиве `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`. Это значение ДОЛЖНО быть кратным 2, поскольку для каждой строки сканирования требуются левый и правый конечные точки.

**Returns:**
int
### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Получает или задает количество.

Значение: Количество горизонтальных (по оси x) координат в массиве `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`. Это значение ДОЛЖНО быть кратным 2, поскольку для каждой строки сканирования требуются левый и правый конечные точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Получает или задает верхнюю границу.

Значение: Вертикальная (по оси y) координата, в логических единицах, верхней строки сканирования.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Получает или задает верхнюю границу.

Значение: Вертикальная (по оси y) координата, в логических единицах, верхней строки сканирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Получает или задает нижнюю границу.

Значение: Вертикальная (по оси y) координата, в логических единицах, нижней строки сканирования.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Получает или задает нижнюю границу.

Значение: Вертикальная (по оси y) координата, в логических единицах, нижней строки сканирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getScanLines() {#getScanLines--}
```
public Point[] getScanLines()
```


Получает или задает строки сканирования.

Значение: Массив строк сканирования, каждая из которых задаётся левыми и правыми горизонтальными (по оси x) координатами её конечных точек.

**Returns:**
com.aspose.imaging.Point[]
### setScanLines(Point[] value) {#setScanLines-com.aspose.imaging.Point---}
```
public void setScanLines(Point[] value)
```


Получает или задает строки сканирования.

Значение: Массив строк сканирования, каждая из которых задаётся левыми и правыми горизонтальными (по оси x) координатами её конечных точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getCount2() {#getCount2--}
```
public int getCount2()
```


Получает или задает count2.

Значение: То же, что значение поля `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`; оно присутствует для обеспечения перемещения вверх по структуре.

**Returns:**
int
### setCount2(int value) {#setCount2-int-}
```
public void setCount2(int value)
```


Получает или задает count2.

Значение: То же, что значение поля `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`; оно присутствует для обеспечения перемещения вверх по структуре.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

