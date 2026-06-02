---
title: "EmfAlphaBlend"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_ALPHABLEND указывает блочную передачу пикселей из исходного битмапа в прямоугольник назначения, включая данные альфа‑прозрачности, согласно заданной операции смешивания."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfAlphaBlend extends EmfBitmapRecordType
```

Запись EMR\_ALPHABLEND определяет блочную передачу пикселей из исходного bitmap в прямоугольник назначения, включая данные альфа-прозрачности, в соответствии с указанной операцией смешивания.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfAlphaBlend(EmfRecord source)](#EmfAlphaBlend-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfAlphaBlend`. |
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
| [getBlendFunction()](#getBlendFunction--) | Получает или задает структуру, которая определяет операции смешивания для исходных и целевых битмапов. |
| [setBlendFunction(EmfBlendFunction value)](#setBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) | Получает или задает структуру, которая определяет операции смешивания для исходных и целевых битмапов. |
| [getXSrc()](#getXSrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла исходного прямоугольника. |
| [setXSrc(int value)](#setXSrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла исходного прямоугольника. |
| [getYSrc()](#getYSrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла исходного прямоугольника. |
| [setYSrc(int value)](#setYSrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла исходного прямоугольника. |
| [getXformSr()](#getXformSr--) | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу. |
| [setXformSr(Matrix value)](#setXformSr-com.aspose.imaging.Matrix-) | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8 который определяет фоновый цвет исходного битмапа. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8 который определяет фоновый цвет исходного битмапа. |
| [getUsageSrc()](#getUsageSrc--) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. |
| [getCxSrc()](#getCxSrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину исходного прямоугольника. |
| [setCxSrc(int value)](#setCxSrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину исходного прямоугольника. |
| [getCySrc()](#getCySrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту исходного прямоугольника. |
| [setCySrc(int value)](#setCySrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту исходного прямоугольника. |
| [getSourceBitmap()](#getSourceBitmap--) | Получает или задает буфер, содержащий исходный битмап, который не обязателен быть смежным с фиксированной частью записи EMR\_ALPHABLEND. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает буфер, содержащий исходный битмап, который не обязателен быть смежным с фиксированной частью записи EMR\_ALPHABLEND. |
### EmfAlphaBlend(EmfRecord source) {#EmfAlphaBlend-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAlphaBlend(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfAlphaBlend`.

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


Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину прямоугольника назначения. Это значение ДОЛЖНО быть больше нуля.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину прямоугольника назначения. Это значение ДОЛЖНО быть больше нуля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту прямоугольника назначения. Это значение ДОЛЖНО быть больше нуля.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту прямоугольника назначения. Это значение ДОЛЖНО быть больше нуля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBlendFunction() {#getBlendFunction--}
```
public EmfBlendFunction getBlendFunction()
```


Получает или задает структуру, которая определяет операции смешивания для исходных и целевых битмапов.

**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
### setBlendFunction(EmfBlendFunction value) {#setBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void setBlendFunction(EmfBlendFunction value)
```


Получает или задает структуру, которая определяет операции смешивания для исходных и целевых битмапов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

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

### getXformSr() {#getXformSr--}
```
public Matrix getXformSr()
```


Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSr(Matrix value) {#setXformSr-com.aspose.imaging.Matrix-}
```
public void setXformSr(Matrix value)
```


Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBkSrcArgb32Color() {#getBkSrcArgb32Color--}
```
public int getBkSrcArgb32Color()
```


Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8 который определяет фоновый цвет исходного битмапа.

Значение: 32-битный цвет ARGB

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8 который определяет фоновый цвет исходного битмапа.

Значение: 32-битный цвет ARGB

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

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину исходного прямоугольника. Это значение ДОЛЖНО быть больше нуля.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину исходного прямоугольника. Это значение ДОЛЖНО быть больше нуля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту исходного прямоугольника. Это значение ДОЛЖНО быть больше нуля.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту исходного прямоугольника. Это значение ДОЛЖНО быть больше нуля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Получает или задает буфер, содержащий исходный битмап, который не обязателен быть смежным с фиксированной частью записи EMR\_ALPHABLEND. Соответственно, поля в этом буфере, помеченные "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Получает или задает буфер, содержащий исходный битмап, который не обязателен быть смежным с фиксированной частью записи EMR\_ALPHABLEND. Соответственно, поля в этом буфере, помеченные "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

