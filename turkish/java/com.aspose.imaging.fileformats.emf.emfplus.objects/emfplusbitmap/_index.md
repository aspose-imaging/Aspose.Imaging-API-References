---
title: "EmfPlusBitmap"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusBitmap nesnesi, grafik görüntüsü içeren bir bitmap'i belirtir."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusBitmap extends EmfPlusBaseImageData
```

EmfPlusBitmap nesnesi, grafik görüntüsü içeren bir bitmap'i belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusBitmap()](#EmfPlusBitmap--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitmapData()](#getBitmapData--) | Alır veya ayarlar bitmap verisi BitmapData (değişken): Tip alanında belirtilen bitmap veri nesnesini tanımlayan değişken uzunlukta veri. |
| [setBitmapData(EmfPlusBaseBitmapData value)](#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-) | Alır veya ayarlar bitmap verisi BitmapData (değişken): Tip alanında belirtilen bitmap veri nesnesini tanımlayan değişken uzunlukta veri. |
| [getHeight()](#getHeight--) | Alır veya ayarlar bitmap yüksekliği Height (4 bayt): Bitmap'in kapladığı alanın piksel cinsinden yüksekliğini belirten 32 bit işaretli tamsayı. |
| [setHeight(int value)](#setHeight-int-) | Alır veya ayarlar bitmap yüksekliği Height (4 bayt): Bitmap'in kapladığı alanın piksel cinsinden yüksekliğini belirten 32 bit işaretli tamsayı. |
| [getPixelFormat()](#getPixelFormat--) | Alır veya ayarlar piksel biçimi PixelFormat (4 bayt): Bitmap görüntüsünü oluşturan piksellerin biçimini belirten 32 bit işaretsiz tamsayı. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Alır veya ayarlar piksel biçimi PixelFormat (4 bayt): Bitmap görüntüsünü oluşturan piksellerin biçimini belirten 32 bit işaretsiz tamsayı. |
| [getStride()](#getStride--) | Alır veya ayarlar görüntünün satır aralığı Stride (4 bayt): Bir tarama satırının başlangıcı ile bir sonrakinin arasındaki bayt ofsetini belirten 32 bit işaretli tamsayı. |
| [setStride(int value)](#setStride-int-) | Alır veya ayarlar görüntünün satır aralığı Stride (4 bayt): Bir tarama satırının başlangıcı ile bir sonrakinin arasındaki bayt ofsetini belirten 32 bit işaretli tamsayı. |
| [getType()](#getType--) | Alır veya ayarlar görüntünün türü Type (4 bayt): BitmapData alanındaki veri türünü belirten 32 bit işaretsiz tamsayı. |
| [setType(int value)](#setType-int-) | Alır veya ayarlar görüntünün türü Type (4 bayt): BitmapData alanındaki veri türünü belirten 32 bit işaretsiz tamsayı. |
| [getWidth()](#getWidth--) | Alır veya ayarlar görüntü genişliği Width (4 bayt): Bitmap'in kapladığı alanın piksel cinsinden genişliğini belirten 32 bit işaretli tamsayı. |
| [setWidth(int value)](#setWidth-int-) | Alır veya ayarlar görüntü genişliği Width (4 bayt): Bitmap'in kapladığı alanın piksel cinsinden genişliğini belirten 32 bit işaretli tamsayı. |
### EmfPlusBitmap() {#EmfPlusBitmap--}
```
public EmfPlusBitmap()
```


### getBitmapData() {#getBitmapData--}
```
public EmfPlusBaseBitmapData getBitmapData()
```


Alır veya ayarlar bitmap verisi BitmapData (değişken): Tip alanında belirtilen bitmap veri nesnesini tanımlayan değişken uzunlukta veri. Verinin içeriği ve biçimi her bitmap türü için farklı olabilir.

Değer: Bitmap verisi.

**Returns:**
[EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
### setBitmapData(EmfPlusBaseBitmapData value) {#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-}
```
public void setBitmapData(EmfPlusBaseBitmapData value)
```


Alır veya ayarlar bitmap verisi BitmapData (değişken): Tip alanında belirtilen bitmap veri nesnesini tanımlayan değişken uzunlukta veri. Verinin içeriği ve biçimi her bitmap türü için farklı olabilir.

Değer: Bitmap verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Alır veya ayarlar bitmap yüksekliği Height (4 bayt): Bitmap'in kapladığı alanın piksel cinsinden yüksekliğini belirten 32 bit işaretli tamsayı. Görüntü, Tip alanına göre sıkıştırılmışsa, bu değer tanımsızdır ve YOK SAYILMASI GEREKİR.

Değer: Yükseklik.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Alır veya ayarlar bitmap yüksekliği Height (4 bayt): Bitmap'in kapladığı alanın piksel cinsinden yüksekliğini belirten 32 bit işaretli tamsayı. Görüntü, Tip alanına göre sıkıştırılmışsa, bu değer tanımsızdır ve YOK SAYILMASI GEREKİR.

Değer: Yükseklik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Alır veya ayarlar piksel biçimi PixelFormat (4 bayt): Bitmap görüntüsünü oluşturan piksellerin biçimini belirten 32 bit işaretsiz tamsayı. Desteklenen piksel biçimleri `EmfPlusPixelFormat` numaralandırmasında (bölüm 2.1.1.25) belirtilir. Görüntü, Tip alanına göre sıkıştırılmışsa, bu değer tanımsızdır ve YOK SAYILMASI GEREKİR.

Değer: Piksel biçimi.

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Alır veya ayarlar piksel biçimi PixelFormat (4 bayt): Bitmap görüntüsünü oluşturan piksellerin biçimini belirten 32 bit işaretsiz tamsayı. Desteklenen piksel biçimleri `EmfPlusPixelFormat` numaralandırmasında (bölüm 2.1.1.25) belirtilir. Görüntü, Tip alanına göre sıkıştırılmışsa, bu değer tanımsızdır ve YOK SAYILMASI GEREKİR.

Değer: Piksel biçimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getStride() {#getStride--}
```
public int getStride()
```


Alır veya ayarlar görüntünün satır aralığı Stride (4 bayt): Bir tarama satırının başlangıcı ile bir sonrakinin arasındaki bayt ofsetini belirten 32 bit işaretli tamsayı. Bu değer, PixelFormat alanında belirtilen piksel başına bayt sayısı ile Width alanında belirtilen piksel genişliğinin çarpımıdır. Bu alanın değeri DÖRT'ün katı OLMAK ZORUNDADIR. Görüntü, Tip alanına göre sıkıştırılmışsa, bu değer tanımsızdır ve YOK SAYILMASI GEREKİR.

Değer: Satır aralığı.

**Returns:**
int
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Alır veya ayarlar görüntünün satır aralığı Stride (4 bayt): Bir tarama satırının başlangıcı ile bir sonrakinin arasındaki bayt ofsetini belirten 32 bit işaretli tamsayı. Bu değer, PixelFormat alanında belirtilen piksel başına bayt sayısı ile Width alanında belirtilen piksel genişliğinin çarpımıdır. Bu alanın değeri DÖRT'ün katı OLMAK ZORUNDADIR. Görüntü, Tip alanına göre sıkıştırılmışsa, bu değer tanımsızdır ve YOK SAYILMASI GEREKİR.

Değer: Satır aralığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getType() {#getType--}
```
public int getType()
```


Alır veya ayarlar görüntünün türü Type (4 bayt): BitmapData alanındaki veri türünü belirten 32 bit işaretsiz tamsayı. Bu değer `EmfPlusBitmapDataType` numaralandırmasında (bölüm 2.1.1.2) tanımlanmış OLMAK ZORUNDADIR.

Değer: Tür.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Alır veya ayarlar görüntünün türü Type (4 bayt): BitmapData alanındaki veri türünü belirten 32 bit işaretsiz tamsayı. Bu değer `EmfPlusBitmapDataType` numaralandırmasında (bölüm 2.1.1.2) tanımlanmış OLMAK ZORUNDADIR.

Değer: Tür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Alır veya ayarlar görüntü genişliği Width (4 bayt): Bitmap'in kapladığı alanın piksel cinsinden genişliğini belirten 32 bit işaretli tamsayı. Görüntü, Tip alanına göre sıkıştırılmışsa, bu değer tanımsızdır ve YOK SAYILMASI GEREKİR.

Değer: Genişlik.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Alır veya ayarlar görüntü genişliği Width (4 bayt): Bitmap'in kapladığı alanın piksel cinsinden genişliğini belirten 32 bit işaretli tamsayı. Görüntü, Tip alanına göre sıkıştırılmışsa, bu değer tanımsızdır ve YOK SAYILMASI GEREKİR.

Değer: Genişlik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

