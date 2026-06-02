---
title: "WmfPatBlt"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись META_PATBLT закрашивает указанный прямоугольник с помощью кисти, которая     определена в контексте устройства воспроизведения."
type: docs
weight: 52
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfpatblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfPointObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfpointobject)
```
public class WmfPatBlt extends WmfPointObject
```

Запись META\_PATBLT закрашивает указанный прямоугольник с помощью кисти, которая определена в контексте устройства воспроизведения. Цвет кисти и цвет(а) поверхности комбинируются с использованием указанной растровой операции.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfPatBlt()](#WmfPatBlt--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Получает или задает растровую операцию. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Получает или задает растровую операцию. |
| [getHeight()](#getHeight--) | Получает или задает высоту. |
| [setHeight(short value)](#setHeight-short-) | Получает или задает высоту. |
| [getWidth()](#getWidth--) | Получает или задает ширину. |
| [setWidth(short value)](#setWidth-short-) | Получает или задает ширину. |
### WmfPatBlt() {#WmfPatBlt--}
```
public WmfPatBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Получает или задает растровую операцию.

Значение: код растровой операции. Этот код ДОЛЖЕН быть одним из значений в таблице перечисления троичной растровой операции.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Получает или задает растровую операцию.

Значение: код растровой операции. Этот код ДОЛЖЕН быть одним из значений в таблице перечисления троичной растровой операции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


Получает или задает высоту.

Значение: высота прямоугольника в логических единицах.

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


Получает или задает высоту.

Значение: высота прямоугольника в логических единицах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


Получает или задает ширину.

Значение: ширина прямоугольника в логических единицах.

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


Получает или задает ширину.

Значение: ширина прямоугольника в логических единицах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

