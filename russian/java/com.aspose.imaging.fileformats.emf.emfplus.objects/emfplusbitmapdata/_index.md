---
title: "EmfPlusBitmapData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusBitmapData указывает bitmap-изображение с данными пикселей."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusBitmapData extends EmfPlusBaseBitmapData
```

Объект EmfPlusBitmapData указывает bitmap-изображение с данными пикселей.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getColors()](#getColors--) | Получает или задает цвета палитры Colors (variable): Необязательный `EmfPlusPalette` объект (section 2.2.2.28), который определяет палитру цветов, используемых в пиксельных данных. |
| [setColors(EmfPlusPalette value)](#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Получает или задает цвета палитры Colors (variable): Необязательный `EmfPlusPalette` объект (section 2.2.2.28), который определяет палитру цветов, используемых в пиксельных данных. |
| [getPixelData()](#getPixelData--) | Получает или задает пиксельные данные PixelData (variable): Массив байтов, определяющих пиксельные данные. |
| [setPixelData(byte[] value)](#setPixelData-byte---) | Получает или задает пиксельные данные PixelData (variable): Массив байтов, определяющих пиксельные данные. |
### EmfPlusBitmapData() {#EmfPlusBitmapData--}
```
public EmfPlusBitmapData()
```


### getColors() {#getColors--}
```
public EmfPlusPalette getColors()
```


Получает или задает цвета палитры Colors (variable): Необязательный `EmfPlusPalette` объект (section 2.2.2.28), который определяет палитру цветов, используемых в пиксельных данных. Это поле MUST присутствовать, если флаг I установлен в поле PixelFormat объекта `EmfPlusBitmap`.

Значение: colors.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setColors(EmfPlusPalette value) {#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setColors(EmfPlusPalette value)
```


Получает или задает цвета палитры Colors (variable): Необязательный `EmfPlusPalette` объект (section 2.2.2.28), который определяет палитру цветов, используемых в пиксельных данных. Это поле MUST присутствовать, если флаг I установлен в поле PixelFormat объекта `EmfPlusBitmap`.

Значение: colors.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

### getPixelData() {#getPixelData--}
```
public byte[] getPixelData()
```


Получает или задает пиксельные данные PixelData (variable): Массив байтов, определяющих пиксельные данные. Размер и формат этих данных могут быть вычислены из полей объекта EmfPlusBitmap, включая формат пикселей из перечисления `Consts.EmfPlusPixelFormat` (section 2.1.1.25).

Value: Пиксельные данные.

**Returns:**
byte[]
### setPixelData(byte[] value) {#setPixelData-byte---}
```
public void setPixelData(byte[] value)
```


Получает или задает пиксельные данные PixelData (variable): Массив байтов, определяющих пиксельные данные. Размер и формат этих данных могут быть вычислены из полей объекта EmfPlusBitmap, включая формат пикселей из перечисления `Consts.EmfPlusPixelFormat` (section 2.1.1.25).

Value: Пиксельные данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

