---
title: "EmfStretchDiBits"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_STRETCHDIBITS задает блочную передачу пикселей из исходного битмапа в прямоугольник назначения, при необходимости в сочетании с шаблоном кисти согласно указанной растровой операции, растягивая или сжимая вывод для соответствия размерам назначения."
type: docs
weight: 150
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchDiBits extends EmfBitmapRecordType
```

Запись EMR\_STRETCHDIBITS указывает блоковую передачу пикселей из исходного битмапа в прямоугольник назначения, при необходимости в комбинации с шаблоном кисти, согласно указанной растровой операции, растягивая или сжимая вывод, чтобы он соответствовал размерам назначения.

Эта запись поддерживает исходные изображения в форматах JPEG и PNG. Поле Compression в заголовке исходного битмапа указывает формат изображения. Если знаки полей высоты и ширины исходного и целевого изображений различаются, запись задаёт копию исходного битмапа в виде зеркального отражения в назначении. То есть, если cxSrc и cxDest имеют разные знаки, задаётся зеркальное изображение исходного битмапа по оси x. Если cySrc и cyDest имеют разные знаки, задаётся зеркальное изображение исходного битмапа по оси y.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfStretchDiBits(EmfRecord source)](#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfStretchDiBits`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник назначения в единицах устройства. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник назначения в единицах устройства. |
| [getXDest()](#getXDest--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла прямоугольника назначения. |
| [setXDest(int value)](#setXDest-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла прямоугольника назначения. |
| [getYDest()](#getYDest--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла прямоугольника назначения. |
| [setYDest(int value)](#setYDest-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла прямоугольника назначения. |
| [getXSrc()](#getXSrc--) | Получает или задает 32‑битное знаковое целое, определяющее координату x в пикселях верхнего левого угла исходного прямоугольника. |
| [setXSrc(int value)](#setXSrc-int-) | Получает или задает 32‑битное знаковое целое, определяющее координату x в пикселях верхнего левого угла исходного прямоугольника. |
| [getYSrc()](#getYSrc--) | Получает или задает 32‑битное знаковое целое, определяющее координату y в пикселях верхнего левого угла исходного прямоугольника. |
| [setYSrc(int value)](#setYSrc-int-) | Получает или задает 32‑битное знаковое целое, определяющее координату y в пикселях верхнего левого угла исходного прямоугольника. |
| [getCxSrc()](#getCxSrc--) | Получает или задает 32‑битное знаковое целое, определяющее ширину в пикселях исходного прямоугольника. |
| [setCxSrc(int value)](#setCxSrc-int-) | Получает или задает 32‑битное знаковое целое, определяющее ширину в пикселях исходного прямоугольника. |
| [getCySrc()](#getCySrc--) | Получает или задает 32‑битное знаковое целое, определяющее высоту в пикселях исходного прямоугольника. |
| [setCySrc(int value)](#setCySrc-int-) | Получает или задает 32‑битное знаковое целое, определяющее высоту в пикселях исходного прямоугольника. |
| [getUsageSrc()](#getUsageSrc--) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Получает или задает 32‑битное беззнаковое целое, определяющее код растровой операции. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее код растровой операции. |
| [getCxDest()](#getCxDest--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину прямоугольника назначения. |
| [setCxDest(int value)](#setCxDest-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину прямоугольника назначения. |
| [getCyDest()](#getCyDest--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту прямоугольника назначения. |
| [setCyDest(int value)](#setCyDest-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту прямоугольника назначения. |
| [getSourceBitmap()](#getSourceBitmap--) | Получает или задает буфер, содержащий исходный битмап, который не обязателен быть смежным с фиксированной частью записи EMR\_STRETCHDIBITS. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает буфер, содержащий исходный битмап, который не обязателен быть смежным с фиксированной частью записи EMR\_STRETCHDIBITS. |
### EmfStretchDiBits(EmfRecord source) {#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchDiBits(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfStretchDiBits`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник назначения в единицах устройства.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник назначения в единицах устройства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла прямоугольника назначения.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла прямоугольника назначения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла прямоугольника назначения.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла прямоугольника назначения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Получает или задает 32‑битное знаковое целое, определяющее координату x в пикселях верхнего левого угла исходного прямоугольника.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Получает или задает 32‑битное знаковое целое, определяющее координату x в пикселях верхнего левого угла исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Получает или задает 32‑битное знаковое целое, определяющее координату y в пикселях верхнего левого угла исходного прямоугольника.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Получает или задает 32‑битное знаковое целое, определяющее координату y в пикселях верхнего левого угла исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Получает или задает 32‑битное знаковое целое, определяющее ширину в пикселях исходного прямоугольника.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Получает или задает 32‑битное знаковое целое, определяющее ширину в пикселях исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Получает или задает 32‑битное знаковое целое, определяющее высоту в пикселях исходного прямоугольника.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Получает или задает 32‑битное знаковое целое, определяющее высоту в пикселях исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. Это значение ДОЛЖНО находиться в перечислении DIBColors (раздел 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. Это значение ДОЛЖНО находиться в перечислении DIBColors (раздел 2.1.9).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


Получает или задает 32‑битное беззнаковое целое, определяющее код растровой операции. Эти коды определяют, как цветовые данные исходного прямоугольника комбинируются с цветовыми данными целевого прямоугольника и, при необходимости, с шаблоном кисти, чтобы получить окончательный цвет.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее код растровой операции. Эти коды определяют, как цветовые данные исходного прямоугольника комбинируются с цветовыми данными целевого прямоугольника и, при необходимости, с шаблоном кисти, чтобы получить окончательный цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину прямоугольника назначения.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину прямоугольника назначения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту прямоугольника назначения.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту прямоугольника назначения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Получает или задает буфер, содержащий исходный битмап, который не обязателен быть смежным с фиксированной частью записи EMR\_STRETCHDIBITS. Соответственно, поля в этом буфере, помеченные как "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Получает или задает буфер, содержащий исходный битмап, который не обязателен быть смежным с фиксированной частью записи EMR\_STRETCHDIBITS. Соответственно, поля в этом буфере, помеченные как "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

