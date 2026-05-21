---
title: "EmfSetDiBitsToDevice"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETDIBITSTODEVICE определяет блочную передачу пикселей из указанных строк сканирования исходного растрового изображения в целевой прямоугольник."
type: docs
weight: 124
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfSetDiBitsToDevice extends EmfBitmapRecordType
```

Запись EMR\_SETDIBITSTODEVICE определяет блочную передачу пикселей из указанных строк сканирования исходного растрового изображения в целевой прямоугольник.

Эта запись поддерживает исходные изображения в форматах JPEG и PNG. Поле Compression в заголовке исходного растрового изображения указывает формат изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetDiBitsToDevice(EmfRecord source)](#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetDiBitsToDevice`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник назначения в единицах устройства. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник назначения в единицах устройства. |
| [getXDest()](#getXDest--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла прямоугольника назначения. |
| [setXDest(int value)](#setXDest-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла прямоугольника назначения. |
| [getYDest()](#getYDest--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла прямоугольника назначения. |
| [setYDest(int value)](#setYDest-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла прямоугольника назначения. |
| [getXSrc()](#getXSrc--) | Получает или задает 32-битное знаковое целое, которое определяет координату x в пикселях нижнего левого угла исходного прямоугольника. |
| [setXSrc(int value)](#setXSrc-int-) | Получает или задает 32-битное знаковое целое, которое определяет координату x в пикселях нижнего левого угла исходного прямоугольника. |
| [getYSrc()](#getYSrc--) | Получает или задает 32-битное знаковое целое, которое определяет координату y в пикселях нижнего левого угла исходного прямоугольника. |
| [setYSrc(int value)](#setYSrc-int-) | Получает или задает 32-битное знаковое целое, которое определяет координату y в пикселях нижнего левого угла исходного прямоугольника. |
| [getCxSrc()](#getCxSrc--) | Получает или задает 32‑битное знаковое целое, определяющее ширину в пикселях исходного прямоугольника. |
| [setCxSrc(int value)](#setCxSrc-int-) | Получает или задает 32‑битное знаковое целое, определяющее ширину в пикселях исходного прямоугольника. |
| [getCySrc()](#getCySrc--) | Получает или задает 32-битное знаковое целое, которое определяет высоту в пикселях исходного прямоугольника |
| [setCySrc(int value)](#setCySrc-int-) | Получает или задает 32-битное знаковое целое, которое определяет высоту в пикселях исходного прямоугольника |
| [getUsageSrc()](#getUsageSrc--) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. |
| [getIStartScan()](#getIStartScan--) | Получает или задает 32-битное беззнаковое целое, которое определяет первую строку сканирования в массиве. |
| [setIStartScan(int value)](#setIStartScan-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет первую строку сканирования в массиве. |
| [getCScans()](#getCScans--) | Получает или задает 32-битное беззнаковое целое, которое определяет количество строк сканирования. |
| [setCScans(int value)](#setCScans-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет количество строк сканирования. |
| [getSourceBitmap()](#getSourceBitmap--) | Получает или задает буфер, содержащий исходный растровый образ, который не обязателен быть смежным с фиксированной частью записи EMR\_SETDIBITSTODEVICE. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает буфер, содержащий исходный растровый образ, который не обязателен быть смежным с фиксированной частью записи EMR\_SETDIBITSTODEVICE. |
### EmfSetDiBitsToDevice(EmfRecord source) {#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetDiBitsToDevice(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetDiBitsToDevice`.

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


Получает или задает 32-битное знаковое целое, которое определяет координату x в пикселях нижнего левого угла исходного прямоугольника.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Получает или задает 32-битное знаковое целое, которое определяет координату x в пикселях нижнего левого угла исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Получает или задает 32-битное знаковое целое, которое определяет координату y в пикселях нижнего левого угла исходного прямоугольника.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Получает или задает 32-битное знаковое целое, которое определяет координату y в пикселях нижнего левого угла исходного прямоугольника.

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


Получает или задает 32-битное знаковое целое, которое определяет высоту в пикселях исходного прямоугольника

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Получает или задает 32-битное знаковое целое, которое определяет высоту в пикселях исходного прямоугольника

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

### getIStartScan() {#getIStartScan--}
```
public int getIStartScan()
```


Получает или задает 32-битное беззнаковое целое, которое определяет первую строку сканирования в массиве.

**Returns:**
int
### setIStartScan(int value) {#setIStartScan-int-}
```
public void setIStartScan(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет первую строку сканирования в массиве.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCScans() {#getCScans--}
```
public int getCScans()
```


Получает или задает 32-битное беззнаковое целое, которое определяет количество строк сканирования.

**Returns:**
int
### setCScans(int value) {#setCScans-int-}
```
public void setCScans(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет количество строк сканирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Получает или задает буфер, содержащий исходный растровый образ, который не обязателен быть смежным с фиксированной частью записи EMR\_SETDIBITSTODEVICE. Соответственно, поля в этом буфере, помеченные как "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Получает или задает буфер, содержащий исходный растровый образ, который не обязателен быть смежным с фиксированной частью записи EMR\_SETDIBITSTODEVICE. Соответственно, поля в этом буфере, помеченные как "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

