---
title: "EmfPlusBitmap"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusBitmap указывает bitmap, содержащий графическое изображение."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusBitmap extends EmfPlusBaseImageData
```

Объект EmfPlusBitmap указывает bitmap, содержащий графическое изображение.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusBitmap()](#EmfPlusBitmap--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBitmapData()](#getBitmapData--) | Получает или задает данные битмапа BitmapData (variable): Данные переменной длины, определяющие объект данных битмапа, указанный в поле Type. |
| [setBitmapData(EmfPlusBaseBitmapData value)](#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-) | Получает или задает данные битмапа BitmapData (variable): Данные переменной длины, определяющие объект данных битмапа, указанный в поле Type. |
| [getHeight()](#getHeight--) | Получает или задает высоту битмапа Height (4 байта): 32-битное знаковое целое, которое определяет высоту в пикселях области, занимаемой битмапом. |
| [setHeight(int value)](#setHeight-int-) | Получает или задает высоту битмапа Height (4 байта): 32-битное знаковое целое, которое определяет высоту в пикселях области, занимаемой битмапом. |
| [getPixelFormat()](#getPixelFormat--) | Получает или задает формат пикселей PixelFormat (4 байта): 32-битное беззнаковое целое, которое определяет формат пикселей, составляющих изображение битмапа. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Получает или задает формат пикселей PixelFormat (4 байта): 32-битное беззнаковое целое, которое определяет формат пикселей, составляющих изображение битмапа. |
| [getStride()](#getStride--) | Получает или задает шаг изображения Stride (4 байта): 32-битное знаковое целое, которое определяет смещение в байтах между началом одной строки сканирования и следующей. |
| [setStride(int value)](#setStride-int-) | Получает или задает шаг изображения Stride (4 байта): 32-битное знаковое целое, которое определяет смещение в байтах между началом одной строки сканирования и следующей. |
| [getType()](#getType--) | Получает или задает тип изображения Type (4 байта): 32-битное беззнаковое целое, которое определяет тип данных в поле BitmapData. |
| [setType(int value)](#setType-int-) | Получает или задает тип изображения Type (4 байта): 32-битное беззнаковое целое, которое определяет тип данных в поле BitmapData. |
| [getWidth()](#getWidth--) | Получает или задает ширину изображения Width (4 байта): 32-битное знаковое целое, которое определяет ширину в пикселях области, занимаемой битмапом. |
| [setWidth(int value)](#setWidth-int-) | Получает или задает ширину изображения Width (4 байта): 32-битное знаковое целое, которое определяет ширину в пикселях области, занимаемой битмапом. |
### EmfPlusBitmap() {#EmfPlusBitmap--}
```
public EmfPlusBitmap()
```


### getBitmapData() {#getBitmapData--}
```
public EmfPlusBaseBitmapData getBitmapData()
```


Получает или задает данные битмапа BitmapData (variable): Данные переменной длины, определяющие объект данных битмапа, указанный в поле Type. Содержание и формат данных могут различаться для каждого типа битмапа.

Значение: данные битмапа.

**Returns:**
[EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
### setBitmapData(EmfPlusBaseBitmapData value) {#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-}
```
public void setBitmapData(EmfPlusBaseBitmapData value)
```


Получает или задает данные битмапа BitmapData (variable): Данные переменной длины, определяющие объект данных битмапа, указанный в поле Type. Содержание и формат данных могут различаться для каждого типа битмапа.

Значение: данные битмапа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает или задает высоту битмапа Height (4 байта): 32-битное знаковое целое, которое определяет высоту в пикселях области, занимаемой битмапом. Если изображение сжато, согласно полю Type, это значение не определено и ДОЛЖНО игнорироваться.

Значение: Высота.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Получает или задает высоту битмапа Height (4 байта): 32-битное знаковое целое, которое определяет высоту в пикселях области, занимаемой битмапом. Если изображение сжато, согласно полю Type, это значение не определено и ДОЛЖНО игнорироваться.

Значение: Высота.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Получает или задает формат пикселей PixelFormat (4 байта): 32-битное беззнаковое целое, которое определяет формат пикселей, составляющих изображение битмапа. Поддерживаемые форматы пикселей указаны в перечислении `EmfPlusPixelFormat` (раздел 2.1.1.25). Если изображение сжато, согласно полю Type, это значение не определено и ДОЛЖНО игнорироваться.

Значение: формат пикселей.

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Получает или задает формат пикселей PixelFormat (4 байта): 32-битное беззнаковое целое, которое определяет формат пикселей, составляющих изображение битмапа. Поддерживаемые форматы пикселей указаны в перечислении `EmfPlusPixelFormat` (раздел 2.1.1.25). Если изображение сжато, согласно полю Type, это значение не определено и ДОЛЖНО игнорироваться.

Значение: формат пикселей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getStride() {#getStride--}
```
public int getStride()
```


Получает или задает шаг изображения Stride (4 байта): 32-битное знаковое целое, которое определяет смещение в байтах между началом одной строки сканирования и следующей. Это значение равно количеству байтов на пиксель, указанному в поле PixelFormat, умноженному на ширину в пикселях, указанную в поле Width. Значение этого поля ДОЛЖНО быть кратным четырём. Если изображение сжато, согласно полю Type, это значение не определено и ДОЛЖНО игнорироваться.

Значение: шаг.

**Returns:**
int
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Получает или задает шаг изображения Stride (4 байта): 32-битное знаковое целое, которое определяет смещение в байтах между началом одной строки сканирования и следующей. Это значение равно количеству байтов на пиксель, указанному в поле PixelFormat, умноженному на ширину в пикселях, указанную в поле Width. Значение этого поля ДОЛЖНО быть кратным четырём. Если изображение сжато, согласно полю Type, это значение не определено и ДОЛЖНО игнорироваться.

Значение: шаг.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public int getType()
```


Получает или задает тип изображения Type (4 байта): 32-битное беззнаковое целое, которое определяет тип данных в поле BitmapData. Это значение ДОЛЖНО быть определено в перечислении `EmfPlusBitmapDataType` (раздел 2.1.1.2).

Значение: тип.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Получает или задает тип изображения Type (4 байта): 32-битное беззнаковое целое, которое определяет тип данных в поле BitmapData. Это значение ДОЛЖНО быть определено в перечислении `EmfPlusBitmapDataType` (раздел 2.1.1.2).

Значение: тип.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает или задает ширину изображения Width (4 байта): 32-битное знаковое целое, которое определяет ширину в пикселях области, занимаемой битмапом. Если изображение сжато, согласно полю Type, это значение не определено и ДОЛЖНО игнорироваться.

Значение: Ширина.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Получает или задает ширину изображения Width (4 байта): 32-битное знаковое целое, которое определяет ширину в пикселях области, занимаемой битмапом. Если изображение сжато, согласно полю Type, это значение не определено и ДОЛЖНО игнорироваться.

Значение: Ширина.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

