---
title: "EmfSetIcmProfileA"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SETICMPROFILEA kaydı, grafik çıktısı için ASCII karakterlerinden oluşan bir ada sahip bir dosyada renk profilini belirtir."
type: docs
weight: 126
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileA extends EmfStateRecordType
```

EMR\_SETICMPROFILEA kaydı, grafik çıktısı için ASCII karakterlerinden oluşan bir ad taşıyan bir dosyada renk profilini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSetIcmProfileA(EmfRecord source)](#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfSetIcmProfileA` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | Renk profili bayraklarını içeren 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setDwFlags(int value)](#setDwFlags-int-) | Renk profili bayraklarını içeren 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getCbName()](#getCbName--) | İstenen renk profilinin ASCII adındaki bayt sayısını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setCbName(int value)](#setCbName-int-) | İstenen renk profilinin ASCII adındaki bayt sayısını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getCbData()](#getCbData--) | Veri alanında bulunuyorsa renk profili verisinin boyutunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setCbData(int value)](#setCbData-int-) | Veri alanında bulunuyorsa renk profili verisinin boyutunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getData()](#getData--) | İstenen renk profilinin ASCII adını ve ham verisini belirten (cbName + cbData) boyutunda bir bayt dizisini alır veya ayarlar. |
| [setData(byte[] value)](#setData-byte---) | İstenen renk profilinin ASCII adını ve ham verisini belirten (cbName + cbData) boyutunda bir bayt dizisini alır veya ayarlar. |
| [getName()](#getName--) | Adı alır |
| [getRawData()](#getRawData--) | Ham veriyi alır |
### EmfSetIcmProfileA(EmfRecord source) {#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileA(EmfRecord source)
```


Yeni bir `EmfSetIcmProfileA` sınıfı örneği başlatır.

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


İstenen renk profilinin ASCII adındaki bayt sayısını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


İstenen renk profilinin ASCII adındaki bayt sayısını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Veri alanında bulunuyorsa renk profili verisinin boyutunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Veri alanında bulunuyorsa renk profili verisinin boyutunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


İstenen renk profilinin ASCII adını ve ham verisini belirten (cbName + cbData) boyutunda bir bayt dizisini alır veya ayarlar.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


İstenen renk profilinin ASCII adını ve ham verisini belirten (cbName + cbData) boyutunda bir bayt dizisini alır veya ayarlar.

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
