---
title: "EmfPlusBitmapData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusBitmapData nesnesi, piksel verileri içeren bir bitmap görüntüsünü belirtir."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusBitmapData extends EmfPlusBaseBitmapData
```

EmfPlusBitmapData nesnesi, piksel verileri içeren bir bitmap görüntüsünü belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColors()](#getColors--) | Alır veya ayarlar palet renkleri Colors (değişken): Piksel verilerinde kullanılan renk paletini belirten isteğe bağlı bir `EmfPlusPalette` nesnesi (bölüm 2.2.2.28). |
| [setColors(EmfPlusPalette value)](#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Alır veya ayarlar palet renkleri Colors (değişken): Piksel verilerinde kullanılan renk paletini belirten isteğe bağlı bir `EmfPlusPalette` nesnesi (bölüm 2.2.2.28). |
| [getPixelData()](#getPixelData--) | Alır veya ayarlar piksel verileri PixelData (değişken): Piksel verilerini belirten bayt dizisi. |
| [setPixelData(byte[] value)](#setPixelData-byte---) | Alır veya ayarlar piksel verileri PixelData (değişken): Piksel verilerini belirten bayt dizisi. |
### EmfPlusBitmapData() {#EmfPlusBitmapData--}
```
public EmfPlusBitmapData()
```


### getColors() {#getColors--}
```
public EmfPlusPalette getColors()
```


Alır veya ayarlar palet renkleri Colors (değişken): Piksel verilerinde kullanılan renk paletini belirten isteğe bağlı bir `EmfPlusPalette` nesnesi (bölüm 2.2.2.28). Bu alan, `EmfPlusBitmap` nesnesinin PixelFormat alanında I bayrağı ayarlıysa BULUNMALIDIR.

Değer: renkler.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setColors(EmfPlusPalette value) {#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setColors(EmfPlusPalette value)
```


Alır veya ayarlar palet renkleri Colors (değişken): Piksel verilerinde kullanılan renk paletini belirten isteğe bağlı bir `EmfPlusPalette` nesnesi (bölüm 2.2.2.28). Bu alan, `EmfPlusBitmap` nesnesinin PixelFormat alanında I bayrağı ayarlıysa BULUNMALIDIR.

Değer: renkler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

### getPixelData() {#getPixelData--}
```
public byte[] getPixelData()
```


Alır veya ayarlar piksel verileri PixelData (değişken): Piksel verilerini belirten bayt dizisi. Bu verinin boyutu ve biçimi, `Consts.EmfPlusPixelFormat` enumarasyonundan (bölüm 2.1.1.25) alınan piksel formatı dahil olmak üzere EmfPlusBitmap nesnesindeki alanlardan hesaplanabilir.

Değer: Piksel verileri.

**Returns:**
byte[]
### setPixelData(byte[] value) {#setPixelData-byte---}
```
public void setPixelData(byte[] value)
```


Alır veya ayarlar piksel verileri PixelData (değişken): Piksel verilerini belirten bayt dizisi. Bu verinin boyutu ve biçimi, `Consts.EmfPlusPixelFormat` enumarasyonundan (bölüm 2.1.1.25) alınan piksel formatı dahil olmak üzere EmfPlusBitmap nesnesindeki alanlardan hesaplanabilir.

Değer: Piksel verileri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

