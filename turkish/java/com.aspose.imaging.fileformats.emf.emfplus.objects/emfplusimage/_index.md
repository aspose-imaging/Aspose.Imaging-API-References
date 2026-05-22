---
title: "EmfPlusImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusImage nesnesi, bitmap veya metafile biçiminde bir grafik görüntüsü belirtir."
type: docs
weight: 47
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImage extends EmfPlusGraphicsObjectType
```

EmfPlusImage nesnesi, bitmap veya metafile biçiminde bir grafik görüntüsü belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusImage()](#EmfPlusImage--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getImageData()](#getImageData--) | Tip alanında belirtilen görüntü verisini tanımlayan Image data Variable-length data'ı alır veya ayarlar. |
| [setImageData(EmfPlusBaseImageData value)](#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-) | Tip alanında belirtilen görüntü verisini tanımlayan Image data Variable-length data'ı alır veya ayarlar. |
| [getType()](#getType--) | image type'ı, ImageData alanındaki veri tipini belirten 32-bit işaretsiz bir tam sayı, alır veya ayarlar. |
| [setType(int value)](#setType-int-) | image type'ı, ImageData alanındaki veri tipini belirten 32-bit işaretsiz bir tam sayı, alır veya ayarlar. |
### EmfPlusImage() {#EmfPlusImage--}
```
public EmfPlusImage()
```


### getImageData() {#getImageData--}
```
public EmfPlusBaseImageData getImageData()
```


Tip alanında belirtilen görüntü verisini tanımlayan Image data Variable-length data'ı alır veya ayarlar. Verinin içeriği ve formatı her görüntü tipi için farklı olabilir.

**Returns:**
[EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
### setImageData(EmfPlusBaseImageData value) {#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-}
```
public void setImageData(EmfPlusBaseImageData value)
```


Tip alanında belirtilen görüntü verisini tanımlayan Image data Variable-length data'ı alır veya ayarlar. Verinin içeriği ve formatı her görüntü tipi için farklı olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata) |  |

### getType() {#getType--}
```
public int getType()
```


Görüntü tipini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer ImageData alanındaki veri tipini belirtir. Bu değer ImageDataType sayımında (bölüm 2.1.1.15) TANIMLANMALIDIR.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Görüntü tipini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer ImageData alanındaki veri tipini belirtir. Bu değer ImageDataType sayımında (bölüm 2.1.1.15) TANIMLANMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

