---
title: "EmfPlusCompressedImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusCompressedImage указывает изображение с сжатыми данными."
type: docs
weight: 31
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusCompressedImage extends EmfPlusBaseBitmapData
```

Объект EmfPlusCompressedImage указывает изображение с сжатыми данными.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusCompressedImage()](#EmfPlusCompressedImage--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCompressedImageData()](#getCompressedImageData--) | Получает или задает массив байтов, определяющих сжатое изображение. |
| [setCompressedImageData(byte[] value)](#setCompressedImageData-byte---) | Получает или задает массив байтов, определяющих сжатое изображение. |
### EmfPlusCompressedImage() {#EmfPlusCompressedImage--}
```
public EmfPlusCompressedImage()
```


### getCompressedImageData() {#getCompressedImageData--}
```
public byte[] getCompressedImageData()
```


Получает или задает массив байтов, определяющих сжатое изображение. Тип сжатия ДОЛЖЕН определяться из самих данных.

Битмапы задаются объектами EmfPlusBitmap (раздел 2.2.2.2). Объект EmfPlusCompressedImage ДОЛЖЕН присутствовать в поле BitmapData объекта EmfPlusBitmap, если в его поле Type указано BitmapDataTypeCompressed. Этот объект является универсальным и используется для различных типов сжатых данных, включая: \\uf0a7 Exchangeable Image File Format (EXIF), как указано в [EXIF]; \\uf0a7 Graphics Interchange Format (GIF), как указано в [GIF]; \\uf0a7 Joint Photographic Experts Group (JPEG), как указано в [JFIF]; \\uf0a7 Portable Network Graphics (PNG), как указано в [RFC2083] и [W3C - PNG]; и \\uf0a7 Tag Image File Format (TIFF), как указано в [RFC3302] и [TIFF].

**Returns:**
byte[]
### setCompressedImageData(byte[] value) {#setCompressedImageData-byte---}
```
public void setCompressedImageData(byte[] value)
```


Получает или задает массив байтов, определяющих сжатое изображение. Тип сжатия ДОЛЖЕН определяться из самих данных.

Битмапы задаются объектами EmfPlusBitmap (раздел 2.2.2.2). Объект EmfPlusCompressedImage ДОЛЖЕН присутствовать в поле BitmapData объекта EmfPlusBitmap, если в его поле Type указано BitmapDataTypeCompressed. Этот объект является универсальным и используется для различных типов сжатых данных, включая: \\uf0a7 Exchangeable Image File Format (EXIF), как указано в [EXIF]; \\uf0a7 Graphics Interchange Format (GIF), как указано в [GIF]; \\uf0a7 Joint Photographic Experts Group (JPEG), как указано в [JFIF]; \\uf0a7 Portable Network Graphics (PNG), как указано в [RFC2083] и [W3C - PNG]; и \\uf0a7 Tag Image File Format (TIFF), как указано в [RFC3302] и [TIFF].

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

