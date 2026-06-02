---
title: "EmfSetIcmProfileW"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SETICMPROFILEW kaydı, grafik çıktısı için Unicode karakterlerinden oluşan bir ada sahip bir dosyada renk profilini tanımlar."
type: docs
weight: 127
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileW extends EmfStateRecordType
```

EMR\_SETICMPROFILEW kaydı, grafik çıktısı için Unicode karakterlerinden oluşan bir ad taşıyan bir dosyada renk profilini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSetIcmProfileW(EmfRecord source)](#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfSetIcmProfileW` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | Renk profili bayraklarını içeren 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setDwFlags(int value)](#setDwFlags-int-) | Renk profili bayraklarını içeren 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getCbName()](#getCbName--) | 32-bit işaretsiz tamsayı alır veya ayarlar ve istenen renk profilinin Unicode UTF16-LE adındaki bayt sayısını belirtir. |
| [setCbName(int value)](#setCbName-int-) | 32-bit işaretsiz tamsayı alır veya ayarlar ve istenen renk profilinin Unicode UTF16-LE adındaki bayt sayısını belirtir. |
| [getCbData()](#getCbData--) | Eğer eklenmişse, renk profili verisinin boyutunu belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. |
| [setCbData(int value)](#setCbData-int-) | Eğer eklenmişse, renk profili verisinin boyutunu belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. |
| [getData()](#getData--) | Alır veya ayarlar, bayt cinsinden (cbName + cbData) boyutunda bir dizi, bu dizi istenen renk profilinin UTF16-LE adını ve ham verisini belirtir. |
| [setData(byte[] value)](#setData-byte---) | Alır veya ayarlar, bayt cinsinden (cbName + cbData) boyutunda bir dizi, bu dizi istenen renk profilinin UTF16-LE adını ve ham verisini belirtir. |
| [getName()](#getName--) | Adı alır |
| [getRawData()](#getRawData--) | Ham veriyi alır |
### EmfSetIcmProfileW(EmfRecord source) {#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileW(EmfRecord source)
```


Yeni bir `EmfSetIcmProfileW` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Renk profili bayraklarını içeren 32 bit işaretsiz tamsayıyı alır veya ayarlar.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Renk profili bayraklarını içeren 32 bit işaretsiz tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


32-bit işaretsiz tamsayı alır veya ayarlar ve istenen renk profilinin Unicode UTF16-LE adındaki bayt sayısını belirtir.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


32-bit işaretsiz tamsayı alır veya ayarlar ve istenen renk profilinin Unicode UTF16-LE adındaki bayt sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Eğer eklenmişse, renk profili verisinin boyutunu belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Eğer eklenmişse, renk profili verisinin boyutunu belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Alır veya ayarlar, bayt cinsinden (cbName + cbData) boyutunda bir dizi, bu dizi istenen renk profilinin UTF16-LE adını ve ham verisini belirtir.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Alır veya ayarlar, bayt cinsinden (cbName + cbData) boyutunda bir dizi, bu dizi istenen renk profilinin UTF16-LE adını ve ham verisini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


Adı alır

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


Ham veriyi alır

**Returns:**
byte[]
