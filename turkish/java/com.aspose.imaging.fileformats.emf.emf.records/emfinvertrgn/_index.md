---
title: "EmfInvertRgn"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_INVERTRGN kaydı, belirtilen bölgede renkleri tersine çevirir."
type: docs
weight: 67
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfInvertRgn extends EmfStateRecordType
```

EMR\_INVERTRGN kaydı, belirtilen bölgedeki renkleri tersine çevirir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfInvertRgn(EmfRecord source)](#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfInvertRgn` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | [MS-WMF] bölüm 2.2.2.19'da belirtilen, sınırlayıcı dikdörtgeni tanımlayan 128 bitlik WMF RectL nesnesini alır veya ayarlar. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | [MS-WMF] bölüm 2.2.2.19'da belirtilen, sınırlayıcı dikdörtgeni tanımlayan 128 bitlik WMF RectL nesnesini alır veya ayarlar. |
| [getRgnDataSize()](#getRgnDataSize--) | Bölge verisinin boyutunu bayt cinsinden belirten 32 bitlik işaretsiz bir tam sayıyı alır veya ayarlar. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Bölge verisinin boyutunu bayt cinsinden belirten 32 bitlik işaretsiz bir tam sayıyı alır veya ayarlar. |
| [getRgnData()](#getRgnData--) | İşlem birimlerinde bir RegionData nesnesini belirten RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar. |
| [setRgnData(byte[] value)](#setRgnData-byte---) | İşlem birimlerinde bir RegionData nesnesini belirten RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar. |
### EmfInvertRgn(EmfRecord source) {#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfInvertRgn(EmfRecord source)
```


`EmfInvertRgn` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


[MS-WMF] bölüm 2.2.2.19'da belirtilen, sınırlayıcı dikdörtgeni tanımlayan 128 bitlik WMF RectL nesnesini alır veya ayarlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


[MS-WMF] bölüm 2.2.2.19'da belirtilen, sınırlayıcı dikdörtgeni tanımlayan 128 bitlik WMF RectL nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Bölge verisinin boyutunu bayt cinsinden belirten 32 bitlik işaretsiz bir tam sayıyı alır veya ayarlar.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Bölge verisinin boyutunu bayt cinsinden belirten 32 bitlik işaretsiz bir tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRgnData() {#getRgnData--}
```
public byte[] getRgnData()
```


İşlem birimlerinde bir RegionData nesnesini belirten RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar.

**Returns:**
byte[]
### setRgnData(byte[] value) {#setRgnData-byte---}
```
public void setRgnData(byte[] value)
```


İşlem birimlerinde bir RegionData nesnesini belirten RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

