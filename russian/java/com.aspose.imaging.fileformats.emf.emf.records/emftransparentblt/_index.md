---
title: "EmfTransparentBlt"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_TRANSPARENTBLT определяет блочную передачу пикселей из исходного растрового изображения в целевой прямоугольник, рассматривая указанный цвет как прозрачный, растягивая или сжимая вывод для соответствия размерам назначения при необходимости."
type: docs
weight: 154
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfTransparentBlt extends EmfBitmapRecordType
```

Запись EMR\_TRANSPARENTBLT указывает блоковую передачу пикселей из исходного битмапа в прямоугольник назначения, рассматривая указанный цвет как прозрачный, растягивая или сжимая вывод, чтобы он соответствовал размерам назначения, при необходимости.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfTransparentBlt(EmfRecord source)](#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfTransparentBlt`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник назначения в единицах устройства. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник назначения в единицах устройства. |
| [getXDest()](#getXDest--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла прямоугольника назначения. |
| [setXDest(int value)](#setXDest-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла прямоугольника назначения. |
| [getYDest()](#getYDest--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла прямоугольника назначения. |
| [setYDest(int value)](#setYDest-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла прямоугольника назначения. |
| [getCxDest()](#getCxDest--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину прямоугольника назначения. |
| [setCxDest(int value)](#setCxDest-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину прямоугольника назначения. |
| [getCyDest()](#getCyDest--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту прямоугольника назначения. |
| [setCyDest(int value)](#setCyDest-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту прямоугольника назначения. |
| [getTransparentArgb32Color()](#getTransparentArgb32Color--) | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который указывает цвет в исходном растровом изображении, рассматриваемый как прозрачный. |
| [setTransparentArgb32Color(int value)](#setTransparentArgb32Color-int-) | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который указывает цвет в исходном растровом изображении, рассматриваемый как прозрачный. |
| [getXSrc()](#getXSrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла исходного прямоугольника. |
| [setXSrc(int value)](#setXSrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла исходного прямоугольника. |
| [getYSrc()](#getYSrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла исходного прямоугольника. |
| [setYSrc(int value)](#setYSrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла исходного прямоугольника. |
| [getXformSrc()](#getXformSrc--) | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу. |
| [getSrcBkArgb32Color()](#getSrcBkArgb32Color--) | Получает или задает объект WMF ColorRef, который указывает цвет фона исходного растрового изображения. |
| [setSrcBkArgb32Color(int value)](#setSrcBkArgb32Color-int-) | Получает или задает объект WMF ColorRef, который указывает цвет фона исходного растрового изображения. |
| [getUsageSrc()](#getUsageSrc--) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. |
| [getCxSrc()](#getCxSrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину исходного прямоугольника. |
| [setCxSrc(int value)](#setCxSrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину исходного прямоугольника. |
| [getCySrc()](#getCySrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту исходного прямоугольника. |
| [setCySrc(int value)](#setCySrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту исходного прямоугольника. |
| [getSourceBitmap()](#getSourceBitmap--) | Получает или задает буфер, содержащий исходное растровое изображение, который не обязан быть смежным с фиксированной частью записи EMR\_TRANSPARENTBLT. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает буфер, содержащий исходное растровое изображение, который не обязан быть смежным с фиксированной частью записи EMR\_TRANSPARENTBLT. |
### EmfTransparentBlt(EmfRecord source) {#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfTransparentBlt(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfTransparentBlt`.

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

### getTransparentArgb32Color() {#getTransparentArgb32Color--}
```
public int getTransparentArgb32Color()
```


Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который указывает цвет в исходном растровом изображении, рассматриваемый как прозрачный.

**Returns:**
int
### setTransparentArgb32Color(int value) {#setTransparentArgb32Color-int-}
```
public void setTransparentArgb32Color(int value)
```


Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который указывает цвет в исходном растровом изображении, рассматриваемый как прозрачный.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла исходного прямоугольника.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла исходного прямоугольника.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getXformSrc() {#getXformSrc--}
```
public Matrix getXformSrc()
```


Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSrc(Matrix value) {#setXformSrc-com.aspose.imaging.Matrix-}
```
public void setXformSrc(Matrix value)
```


Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getSrcBkArgb32Color() {#getSrcBkArgb32Color--}
```
public int getSrcBkArgb32Color()
```


Получает или задает объект WMF ColorRef, который указывает цвет фона исходного растрового изображения.

**Returns:**
int
### setSrcBkArgb32Color(int value) {#setSrcBkArgb32Color-int-}
```
public void setSrcBkArgb32Color(int value)
```


Получает или задает объект WMF ColorRef, который указывает цвет фона исходного растрового изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Получает или задает 32-битное беззнаковое целое, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного растрового изображения. Это значение ДОЛЖНО находиться в перечислении DIBColors (раздел 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного растрового изображения. Это значение ДОЛЖНО находиться в перечислении DIBColors (раздел 2.1.9).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину исходного прямоугольника.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту исходного прямоугольника.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту исходного прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Получает или задает буфер, содержащий исходное растровое изображение, который не обязан быть смежным с фиксированной частью записи EMR\_TRANSPARENTBLT. Соответственно, поля в этом буфере, помеченные как "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Получает или задает буфер, содержащий исходное растровое изображение, который не обязан быть смежным с фиксированной частью записи EMR\_TRANSPARENTBLT. Соответственно, поля в этом буфере, помеченные как "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

