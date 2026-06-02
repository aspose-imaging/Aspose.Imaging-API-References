---
title: "EmfPlusImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusImage задает графическое изображение в виде растрового изображения или метафайла."
type: docs
weight: 47
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImage extends EmfPlusGraphicsObjectType
```

Объект EmfPlusImage задает графическое изображение в виде растрового изображения или метафайла.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusImage()](#EmfPlusImage--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getImageData()](#getImageData--) | Получает или задает переменной длины данные Image, которые определяют данные изображения, указанные в поле Type. |
| [setImageData(EmfPlusBaseImageData value)](#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-) | Получает или задает переменной длины данные Image, которые определяют данные изображения, указанные в поле Type. |
| [getType()](#getType--) | Получает или задает тип изображения — 32-битное беззнаковое целое, которое определяет тип данных в поле ImageData. |
| [setType(int value)](#setType-int-) | Получает или задает тип изображения — 32-битное беззнаковое целое, которое определяет тип данных в поле ImageData. |
### EmfPlusImage() {#EmfPlusImage--}
```
public EmfPlusImage()
```


### getImageData() {#getImageData--}
```
public EmfPlusBaseImageData getImageData()
```


Получает или задает переменной длины данные Image, которые определяют данные изображения, указанные в поле Type. Содержание и формат данных могут различаться для каждого типа изображения.

**Returns:**
[EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
### setImageData(EmfPlusBaseImageData value) {#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-}
```
public void setImageData(EmfPlusBaseImageData value)
```


Получает или задает переменной длины данные Image, которые определяют данные изображения, указанные в поле Type. Содержание и формат данных могут различаться для каждого типа изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata) |  |

### getType() {#getType--}
```
public int getType()
```


Получает или задает тип изображения — 32-битное беззнаковое целое, которое указывает тип данных в поле ImageData. Это значение ДОЛЖНО быть определено в перечислении ImageDataType (раздел 2.1.1.15).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Получает или задает тип изображения — 32-битное беззнаковое целое, которое указывает тип данных в поле ImageData. Это значение ДОЛЖНО быть определено в перечислении ImageDataType (раздел 2.1.1.15).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

