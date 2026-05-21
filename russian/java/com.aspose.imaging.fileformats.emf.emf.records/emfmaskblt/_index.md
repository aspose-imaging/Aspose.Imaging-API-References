---
title: "EmfMaskBlt"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_MASKBLT определяет блочную передачу пикселей из исходного растрового изображения в прямоугольник назначения, опционально в сочетании с шаблоном кисти и применением цветовой маски в соответствии с указанными растровыми операциями переднего и заднего плана."
type: docs
weight: 69
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfMaskBlt extends EmfBitmapRecordType
```

Запись EMR\_MASKBLT определяет блочную передачу пикселей из исходного растрового изображения в прямоугольник назначения, опционально в сочетании с шаблоном кисти и применением растровой маски цвета, в соответствии с указанными растровыми операциями переднего и заднего плана.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfMaskBlt(EmfRecord source)](#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfMaskBlt`. |
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
| [getRop4()](#getRop4--) | Получает или задает четверичную растровую операцию, которая определяет тернарные растровые операции для цветов переднего и заднего плана растрового изображения. |
| [setRop4(EmfRop4 value)](#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-) | Получает или задает четверичную растровую операцию, которая определяет тернарные растровые операции для цветов переднего и заднего плана растрового изображения. |
| [getXSrc()](#getXSrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла исходного прямоугольника. |
| [setXSrc(int value)](#setXSrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла исходного прямоугольника. |
| [getYSrc()](#getYSrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла исходного прямоугольника. |
| [setYSrc(int value)](#setYSrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла исходного прямоугольника. |
| [getXformSrc()](#getXformSrc--) | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу. |
| [getArgb32BkColorSrc()](#getArgb32BkColorSrc--) | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8 который определяет фоновый цвет исходного битмапа. |
| [setArgb32BkColorSrc(int value)](#setArgb32BkColorSrc-int-) | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8 который определяет фоновый цвет исходного битмапа. |
| [getUsageSrc()](#getUsageSrc--) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. |
| [getXMask()](#getXMask--) | Получает или задает 32-битное знаковое целое, которое определяет логическую координату x верхнего левого угла маски растрового изображения. |
| [setXMask(int value)](#setXMask-int-) | Получает или задает 32-битное знаковое целое, которое определяет логическую координату x верхнего левого угла маски растрового изображения. |
| [getYMask()](#getYMask--) | Получает или задает 32-битное знаковое целое, которое определяет логическую координату y верхнего левого угла маски растрового изображения. |
| [setYMask(int value)](#setYMask-int-) | Получает или задает 32-битное знаковое целое, которое определяет логическую координату y верхнего левого угла маски растрового изображения. |
| [getUsageMask()](#getUsageMask--) | Получает или задает 32-битное беззнаковое целое, которое определяет способ интерпретации значений в таблице цветов заголовка маски растрового изображения. |
| [setUsageMask(int value)](#setUsageMask-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет способ интерпретации значений в таблице цветов заголовка маски растрового изображения. |
| [getSourceBitmap()](#getSourceBitmap--) | Получает или задает буфер, содержащий исходные растровые изображения, которые не обязаны быть смежными с фиксированной частью записи EMR\_MASKBLT или друг с другом. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает буфер, содержащий исходные растровые изображения, которые не обязаны быть смежными с фиксированной частью записи EMR\_MASKBLT или друг с другом. |
| [getMaskBitmap()](#getMaskBitmap--) | Получает или задает буфер, содержащий маски растровых изображений, которые не обязаны быть смежными с фиксированной частью записи EMR\_MASKBLT или друг с другом. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает буфер, содержащий маски растровых изображений, которые не обязаны быть смежными с фиксированной частью записи EMR\_MASKBLT или друг с другом. |
### EmfMaskBlt(EmfRecord source) {#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMaskBlt(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfMaskBlt`.

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

### getRop4() {#getRop4--}
```
public EmfRop4 getRop4()
```


Получает или задает четверичную растровую операцию, которая определяет тернарные растровые операции для цветов переднего и заднего плана растрового изображения. Эти значения определяют, как данные цвета исходного прямоугольника должны быть объединены с данными цвета прямоугольника назначения.

**Returns:**
[EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4)
### setRop4(EmfRop4 value) {#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-}
```
public void setRop4(EmfRop4 value)
```


Получает или задает четверичную растровую операцию, которая определяет тернарные растровые операции для цветов переднего и заднего плана растрового изображения. Эти значения определяют, как данные цвета исходного прямоугольника должны быть объединены с данными цвета прямоугольника назначения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4) |  |

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

### getArgb32BkColorSrc() {#getArgb32BkColorSrc--}
```
public int getArgb32BkColorSrc()
```


Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8 который определяет фоновый цвет исходного битмапа.

**Returns:**
int
### setArgb32BkColorSrc(int value) {#setArgb32BkColorSrc-int-}
```
public void setArgb32BkColorSrc(int value)
```


Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8 который определяет фоновый цвет исходного битмапа.

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

### getXMask() {#getXMask--}
```
public int getXMask()
```


Получает или задает 32-битное знаковое целое, которое определяет логическую координату x верхнего левого угла маски растрового изображения.

**Returns:**
int
### setXMask(int value) {#setXMask-int-}
```
public void setXMask(int value)
```


Получает или задает 32-битное знаковое целое, которое определяет логическую координату x верхнего левого угла маски растрового изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getYMask() {#getYMask--}
```
public int getYMask()
```


Получает или задает 32-битное знаковое целое, которое определяет логическую координату y верхнего левого угла маски растрового изображения.

**Returns:**
int
### setYMask(int value) {#setYMask-int-}
```
public void setYMask(int value)
```


Получает или задает 32-битное знаковое целое, которое определяет логическую координату y верхнего левого угла маски растрового изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getUsageMask() {#getUsageMask--}
```
public int getUsageMask()
```


Получает или задает 32-битное беззнаковое целое, которое определяет способ интерпретации значений в таблице цветов заголовка маски растрового изображения. Это значение ДОЛЖНО находиться в перечислении DIBColors.

**Returns:**
int
### setUsageMask(int value) {#setUsageMask-int-}
```
public void setUsageMask(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет способ интерпретации значений в таблице цветов заголовка маски растрового изображения. Это значение ДОЛЖНО находиться в перечислении DIBColors.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Получает или задает буфер, содержащий исходные растровые изображения, которые не обязаны быть смежными с фиксированной частью записи EMR\_MASKBLT или друг с другом. Соответственно, поля в этом буфере, помеченные как "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Получает или задает буфер, содержащий исходные растровые изображения, которые не обязаны быть смежными с фиксированной частью записи EMR\_MASKBLT или друг с другом. Соответственно, поля в этом буфере, помеченные как "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


Получает или задает буфер, содержащий маски растровых изображений, которые не обязаны быть смежными с фиксированной частью записи EMR\_MASKBLT или друг с другом. Соответственно, поля в этом буфере, помеченные как "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


Получает или задает буфер, содержащий маски растровых изображений, которые не обязаны быть смежными с фиксированной частью записи EMR\_MASKBLT или друг с другом. Соответственно, поля в этом буфере, помеченные как "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

