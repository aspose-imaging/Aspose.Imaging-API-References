---
title: "EmfPlgBlt"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_PLGBLT задает блочную передачу пикселей из исходного битмапа в целевой параллелограмм с применением битмапа цветовой маски."
type: docs
weight: 84
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfPlgBlt extends EmfBitmapRecordType
```

Запись EMR_PLGBLT задаёт блочную передачу пикселей из исходного растрового изображения в целевой параллелограмм с применением маски цвета.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlgBlt(EmfRecord source)](#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfPlgBlt`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), определяющий ограничивающий прямоугольник в единицах устройства для вывода в назначение. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), определяющий ограничивающий прямоугольник в единицах устройства для вывода в назначение. |
| [getAptlDest()](#getAptlDest--) | Получает или задает массив из трех объектов WMF PointL ([MS-WMF] раздел 2.2.2.15), который задает три угла параллелограммной области назначения для блочного переноса. |
| [setAptlDest(Point[] value)](#setAptlDest-com.aspose.imaging.Point---) | Получает или задает массив из трех объектов WMF PointL ([MS-WMF] раздел 2.2.2.15), который задает три угла параллелограммной области назначения для блочного переноса. |
| [getXSrc()](#getXSrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла исходного прямоугольника. |
| [setXSrc(int value)](#setXSrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую x‑координату верхнего левого угла исходного прямоугольника. |
| [getYSrc()](#getYSrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла исходного прямоугольника. |
| [setYSrc(int value)](#setYSrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую y‑координату верхнего левого угла исходного прямоугольника. |
| [getCxSrc()](#getCxSrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину исходного прямоугольника. |
| [setCxSrc(int value)](#setCxSrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую ширину исходного прямоугольника. |
| [getCySrc()](#getCySrc--) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту исходного прямоугольника. |
| [setCySrc(int value)](#setCySrc-int-) | Получает или задает 32‑битное знаковое целое число, которое указывает логическую высоту исходного прямоугольника. |
| [getXFormSrc()](#getXFormSrc--) | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу. |
| [setXFormSrc(Matrix value)](#setXFormSrc-com.aspose.imaging.Matrix-) | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет цвет фона исходного растрового изображения. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет цвет фона исходного растрового изображения. |
| [getUsageSrc()](#getUsageSrc--) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного битмапа. |
| [getXMask()](#getXMask--) | Получает или задает 32-битное знаковое целое, которое определяет логическую координату x верхнего левого угла маски растрового изображения. |
| [setXMask(int value)](#setXMask-int-) | Получает или задает 32-битное знаковое целое, которое определяет логическую координату x верхнего левого угла маски растрового изображения. |
| [getYMask()](#getYMask--) | Получает или задает 32-битное знаковое целое, которое определяет логическую координату y верхнего левого угла маски растрового изображения. |
| [setYMask(int value)](#setYMask-int-) | Получает или задает 32-битное знаковое целое, которое определяет логическую координату y верхнего левого угла маски растрового изображения. |
| [getUsageMask()](#getUsageMask--) | Получает или задает 32-битное беззнаковое целое, которое определяет способ интерпретации значений в таблице цветов заголовка маски растрового изображения. |
| [setUsageMask(int value)](#setUsageMask-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет способ интерпретации значений в таблице цветов заголовка маски растрового изображения. |
| [getSourceBitmap()](#getSourceBitmap--) | Получает или задает буфер, содержащий исходный растровый образ, который не обязан быть непрерывным с фиксированной частью записи EMR\\_PLGBLT или с другими. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает буфер, содержащий исходный растровый образ, который не обязан быть непрерывным с фиксированной частью записи EMR\\_PLGBLT или с другими. |
| [getMaskBitmap()](#getMaskBitmap--) | Получает или задает буфер, содержащий маску растрового изображения, который не обязан быть непрерывным с фиксированной частью записи EMR\\_PLGBLT или с другими. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает буфер, содержащий маску растрового изображения, который не обязан быть непрерывным с фиксированной частью записи EMR\\_PLGBLT или с другими. |
### EmfPlgBlt(EmfRecord source) {#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPlgBlt(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfPlgBlt`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), определяющий ограничивающий прямоугольник в единицах устройства для вывода в назначение.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), определяющий ограничивающий прямоугольник в единицах устройства для вывода в назначение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAptlDest() {#getAptlDest--}
```
public Point[] getAptlDest()
```


Получает или задает массив из трех объектов WMF PointL ([MS-WMF] раздел 2.2.2.15), который задает три угла параллелограммной области назначения для блочного переноса. Верхний левый угол исходного прямоугольника отображается в первую точку этого массива, верхний правый — во вторую точку, а нижний левый — в третью точку. Нижний правый угол исходного прямоугольника отображается в неявную четвертую точку параллелограмма, которая вычисляется из первых трех точек (A, B и C), рассматривая их как векторы. D = B + C A

**Returns:**
com.aspose.imaging.Point[]
### setAptlDest(Point[] value) {#setAptlDest-com.aspose.imaging.Point---}
```
public void setAptlDest(Point[] value)
```


Получает или задает массив из трех объектов WMF PointL ([MS-WMF] раздел 2.2.2.15), который задает три угла параллелограммной области назначения для блочного переноса. Верхний левый угол исходного прямоугольника отображается в первую точку этого массива, верхний правый — во вторую точку, а нижний левый — в третью точку. Нижний правый угол исходного прямоугольника отображается в неявную четвертую точку параллелограмма, которая вычисляется из первых трех точек (A, B и C), рассматривая их как векторы. D = B + C A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

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

### getXFormSrc() {#getXFormSrc--}
```
public Matrix getXFormSrc()
```


Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXFormSrc(Matrix value) {#setXFormSrc-com.aspose.imaging.Matrix-}
```
public void setXFormSrc(Matrix value)
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


Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет цвет фона исходного растрового изображения.

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет цвет фона исходного растрового изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Получает или задает 32-битное беззнаковое целое, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного растрового изображения. Это значение ДОЛЖНО находиться в перечислении DIBColors.

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет, как интерпретировать значения в таблице цветов заголовка исходного растрового изображения. Это значение ДОЛЖНО находиться в перечислении DIBColors.

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


Получает или задает буфер, содержащий исходный растровый образ, который не обязан быть непрерывным с фиксированной частью записи EMR\\_PLGBLT или с другими. Соответственно, поля в этом буфере, помеченные как \"UndefinedSpace\", являются необязательными и ДОЛЖНЫ игнорироваться.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Получает или задает буфер, содержащий исходный растровый образ, который не обязан быть непрерывным с фиксированной частью записи EMR\\_PLGBLT или с другими. Соответственно, поля в этом буфере, помеченные как \"UndefinedSpace\", являются необязательными и ДОЛЖНЫ игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


Получает или задает буфер, содержащий маску растрового образа, который не обязан быть непрерывным с фиксированной частью записи EMR\\_PLGBLT или с другими. Соответственно, поля в этом буфере, помеченные как \"UndefinedSpace\", являются необязательными и ДОЛЖНЫ игнорироваться.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


Получает или задает буфер, содержащий маску растрового образа, который не обязан быть непрерывным с фиксированной частью записи EMR\\_PLGBLT или с другими. Соответственно, поля в этом буфере, помеченные как \"UndefinedSpace\", являются необязательными и ДОЛЖНЫ игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

