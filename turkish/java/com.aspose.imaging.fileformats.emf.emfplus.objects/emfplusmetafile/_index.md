---
title: "EmfPlusMetafile"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusMetafileData nesnesi, bir grafik görüntüsü içeren metafili belirtir."
type: docs
weight: 55
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusMetafile extends EmfPlusBaseImageData
```

EmfPlusMetafileData nesnesi, bir grafik görüntüsü içeren metafili belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusMetafile()](#EmfPlusMetafile--) | `EmfPlusMetafile` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | 32-bit işaretsiz tam sayı alır veya ayarlar; bu sayı MetafileData alanına gömülü metafilenin türünü belirtir. |
| [setType(int value)](#setType-int-) | 32-bit işaretsiz tam sayı alır veya ayarlar; bu sayı MetafileData alanına gömülü metafilenin türünü belirtir. |
| [getMetafileDataSize()](#getMetafileDataSize--) | 32-bit işaretsiz tam sayı alır veya ayarlar; bu sayı MetafileData alanındaki metafile verisinin bayt cinsinden boyutunu belirtir. |
| [setMetafileDataSize(int value)](#setMetafileDataSize-int-) | 32-bit işaretsiz tam sayı alır veya ayarlar; bu sayı MetafileData alanındaki metafile verisinin bayt cinsinden boyutunu belirtir. |
| [getMetafileData()](#getMetafileData--) | Değişken uzunlukta veri alır veya ayarlar; bu veri gömülü metafileyi belirtir. |
| [setMetafileData(byte[] value)](#setMetafileData-byte---) | Değişken uzunlukta veri alır veya ayarlar; bu veri gömülü metafileyi belirtir. |
### EmfPlusMetafile() {#EmfPlusMetafile--}
```
public EmfPlusMetafile()
```


`EmfPlusMetafile` sınıfının yeni bir örneğini başlatır.

### getType() {#getType--}
```
public int getType()
```


32-bit işaretsiz tam sayı alır veya ayarlar; bu sayı MetafileData alanına gömülü metafilenin türünü belirtir. Bu değer MetafileDataType numaralandırmasında (bölüm 2.1.1.21) tanımlanmış olmalıdır.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


32-bit işaretsiz tam sayı alır veya ayarlar; bu sayı MetafileData alanına gömülü metafilenin türünü belirtir. Bu değer MetafileDataType numaralandırmasında (bölüm 2.1.1.21) tanımlanmış olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMetafileDataSize() {#getMetafileDataSize--}
```
public int getMetafileDataSize()
```


32-bit işaretsiz tam sayı alır veya ayarlar; bu sayı MetafileData alanındaki metafile verisinin bayt cinsinden boyutunu belirtir.

**Returns:**
int
### setMetafileDataSize(int value) {#setMetafileDataSize-int-}
```
public void setMetafileDataSize(int value)
```


32-bit işaretsiz tam sayı alır veya ayarlar; bu sayı MetafileData alanındaki metafile verisinin bayt cinsinden boyutunu belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMetafileData() {#getMetafileData--}
```
public byte[] getMetafileData()
```


Değişken uzunlukta veri alır veya ayarlar; bu veri gömülü metafileyi belirtir. Verinin içeriği ve biçimi her metafile türü için farklı olabilir.

Grafik görüntüleri EmfPlusImage nesneleri (bölüm 2.2.1.4) tarafından belirtilir. ImageTypeMetafile, nesnenin Type alanında belirtilmişse, bir EmfPlusMetafile nesnesi bir EmfPlusImage nesnesinin ImageData alanında VAR OLMALIDIR. Bu nesne geneldir ve farklı veri türleri için kullanılır, şunlar dahil: A WMF metafile [MS-WMF]; yerleştirilebilen WMF metafile; Bir EMF metafile [MS-EMF]; Yalnızca EMF+ kayıtlarıyla grafik işlemlerini belirten bir EMF+ metafile; ve EMF+ ve EMF kayıtlarıyla grafik işlemlerini belirten bir EMF+ metafile. Ek yapı nesnelerinin tanımı için bölüm 2.2.2'ye bakınız.

**Returns:**
byte[]
### setMetafileData(byte[] value) {#setMetafileData-byte---}
```
public void setMetafileData(byte[] value)
```


Değişken uzunlukta veri alır veya ayarlar; bu veri gömülü metafileyi belirtir. Verinin içeriği ve biçimi her metafile türü için farklı olabilir.

Grafik görüntüleri EmfPlusImage nesneleri (bölüm 2.2.1.4) tarafından belirtilir. ImageTypeMetafile, nesnenin Type alanında belirtilmişse, bir EmfPlusMetafile nesnesi bir EmfPlusImage nesnesinin ImageData alanında VAR OLMALIDIR. Bu nesne geneldir ve farklı veri türleri için kullanılır, şunlar dahil: A WMF metafile [MS-WMF]; yerleştirilebilen WMF metafile; Bir EMF metafile [MS-EMF]; Yalnızca EMF+ kayıtlarıyla grafik işlemlerini belirten bir EMF+ metafile; ve EMF+ ve EMF kayıtlarıyla grafik işlemlerini belirten bir EMF+ metafile. Ek yapı nesnelerinin tanımı için bölüm 2.2.2'ye bakınız.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

