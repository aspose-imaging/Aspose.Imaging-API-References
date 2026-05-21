---
title: "WmfStretchDib"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект wmf Stretch DIB."
type: docs
weight: 94
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchdib/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfStretchDib extends WmfObject
```

Объект wmf Stretch DIB.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfStretchDib()](#WmfStretchDib--) | WMFs запись. |
## Методы

| Метод | Описание |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Получает или задает растровую операцию. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Получает или задает растровую операцию. |
| [getColorUsage()](#getColorUsage--) | Получает или задает использование цвета. |
| [setColorUsage(int value)](#setColorUsage-int-) | Получает или задает использование цвета. |
| [getSrcHeight()](#getSrcHeight--) | Получает или задает высоту источника. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Получает или задает высоту источника. |
| [getSrcWidth()](#getSrcWidth--) | Получает или задает ширину источника. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Получает или задает ширину источника. |
| [getYSrc()](#getYSrc--) | Получает или задает y-координату источника. |
| [setYSrc(short value)](#setYSrc-short-) | Получает или задает y-координату источника. |
| [getXSrc()](#getXSrc--) | Получает или задает x-координату источника. |
| [setXSrc(short value)](#setXSrc-short-) | Получает или задает x-координату источника. |
| [getDestHeight()](#getDestHeight--) | Получает или задает высоту назначения. |
| [setDestHeight(short value)](#setDestHeight-short-) | Получает или задает высоту назначения. |
| [getDestWidth()](#getDestWidth--) | Получает или задает ширину назначения. |
| [setDestWidth(short value)](#setDestWidth-short-) | Получает или задает ширину назначения. |
| [getYDest()](#getYDest--) | Получает или задает y-координату назначения. |
| [setYDest(short value)](#setYDest-short-) | Получает или задает y-координату назначения. |
| [getXDest()](#getXDest--) | Получает или задает x-координату назначения. |
| [setXDest(short value)](#setXDest-short-) | Получает или задает x-координату назначения. |
| [getSourceBitmap()](#getSourceBitmap--) | Получает или задает исходный битмап. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает исходный битмап. |
### WmfStretchDib() {#WmfStretchDib--}
```
public WmfStretchDib()
```


WMFs запись.

### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Получает или задает растровую операцию.

Значение: Текущая кисть в контексте устройства воспроизведения, а пиксели назначения должны быть объединены для формирования нового изображения. Этот код ДОЛЖЕН быть одним из значений в перечислении Троичной растровой операции (раздел 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Получает или задает растровую операцию.

Значение: Текущая кисть в контексте устройства воспроизведения, а пиксели назначения должны быть объединены для формирования нового изображения. Этот код ДОЛЖЕН быть одним из значений в перечислении Троичной растровой операции (раздел 2.1.1.31).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Получает или задает использование цвета.

Значение:

Поле Colors в DIB содержит явные значения RGB или индексы в палитру. Это значение ДОЛЖНО находиться в `com.aspose.imaging.fileFormats.wmf.objects.wmfStretchDib.ColorUsage`

Перечисление (раздел 2.1.1.6).

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Получает или задает использование цвета.

Значение:

Поле Colors в DIB содержит явные значения RGB или индексы в палитру. Это значение ДОЛЖНО находиться в `com.aspose.imaging.fileFormats.wmf.objects.wmfStretchDib.ColorUsage`

Перечисление (раздел 2.1.1.6).

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

Значение: Ширина, в логических единицах, исходного прямоугольника.

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Получает или задает ширину источника.

Значение: Ширина, в логических единицах, исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getYSrc() {#getYSrc--}
```
public short getYSrc()
```


Получает или задает y-координату источника.

Значение: y‑координата, в логических единицах, верхнего левого угла исходного прямоугольника.

**Returns:**
short
### setYSrc(short value) {#setYSrc-short-}
```
public void setYSrc(short value)
```


Получает или задает y-координату источника.

Значение: y‑координата, в логических единицах, верхнего левого угла исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getXSrc() {#getXSrc--}
```
public short getXSrc()
```


Получает или задает x-координату источника.

Значение: x‑координата, в логических единицах, верхнего левого угла исходного прямоугольника.

**Returns:**
short
### setXSrc(short value) {#setXSrc-short-}
```
public void setXSrc(short value)
```


Получает или задает x-координату источника.

Значение: x‑координата, в логических единицах, верхнего левого угла исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

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

### getYDest() {#getYDest--}
```
public short getYDest()
```


Получает или задает y-координату назначения.

Значение: y‑координата, в логических единицах, верхнего левого угла прямоугольника назначения.

**Returns:**
short
### setYDest(short value) {#setYDest-short-}
```
public void setYDest(short value)
```


Получает или задает y-координату назначения.

Значение: y‑координата, в логических единицах, верхнего левого угла прямоугольника назначения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getXDest() {#getXDest--}
```
public short getXDest()
```


Получает или задает x-координату назначения.

Значение: x‑координата, в логических единицах, верхнего левого угла прямоугольника назначения.

**Returns:**
short
### setXDest(short value) {#setXDest-short-}
```
public void setXDest(short value)
```


Получает или задает x-координату назначения.

Значение: x‑координата, в логических единицах, верхнего левого угла прямоугольника назначения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Получает или задает исходный битмап.

Значение: Исходный растровый образ.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Получает или задает исходный битмап.

Значение: Исходный растровый образ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

