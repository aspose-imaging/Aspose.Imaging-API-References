---
title: "EmfCommentMultiFormats"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_COMMENT_MULTIFORMATS kaydı, bir görüntüyü birden çok grafik biçiminde belirtir."
type: docs
weight: 30
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentMultiFormats extends EmfCommentPublicRecordType
```

EMR_COMMENT_MULTIFORMATS kaydı bir görüntüyü birden çok grafik formatında belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfCommentMultiFormats(EmfRecord source)](#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfCommentMultiFormats` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOutputRect()](#getOutputRect--) | Mantıksal koordinatlarda çıkış dikdörtgenini belirten bir WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. |
| [setOutputRect(Rectangle value)](#setOutputRect-com.aspose.imaging.Rectangle-) | Mantıksal koordinatlarda çıkış dikdörtgenini belirten bir WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. |
| [getAFormats()](#getAFormats--) | Tercih sırasına göre, EmrFormat nesneleri (bölüm 2.2.4) tarafından belirtilen grafik biçimlerinin CountFormats uzunluğundaki bir dizisini alır veya ayarlar. |
| [setAFormats(EmfFormat[] value)](#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---) | Tercih sırasına göre, EmrFormat nesneleri (bölüm 2.2.4) tarafından belirtilen grafik biçimlerinin CountFormats uzunluğundaki bir dizisini alır veya ayarlar. |
| [getFormatData()](#getFormatData--) | Bu kayıtta bulunan tüm grafik biçimleri için görüntü verisinin baytlarından oluşan değişken uzunlukta bir dizi alır veya ayarlar. |
| [setFormatData(byte[][] value)](#setFormatData-byte-----) | Bu kayıtta bulunan tüm grafik biçimleri için görüntü verisinin baytlarından oluşan değişken uzunlukta bir dizi alır veya ayarlar. |
### EmfCommentMultiFormats(EmfRecord source) {#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentMultiFormats(EmfRecord source)
```


`EmfCommentMultiFormats` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getOutputRect() {#getOutputRect--}
```
public Rectangle getOutputRect()
```


Mantıksal koordinatlarda çıkış dikdörtgenini belirten bir WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setOutputRect(Rectangle value) {#setOutputRect-com.aspose.imaging.Rectangle-}
```
public void setOutputRect(Rectangle value)
```


Mantıksal koordinatlarda çıkış dikdörtgenini belirten bir WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAFormats() {#getAFormats--}
```
public EmfFormat[] getAFormats()
```


Tercih sırasına göre, EmrFormat nesneleri (bölüm 2.2.4) tarafından belirtilen grafik biçimlerinin CountFormats uzunluğundaki bir dizisini alır veya ayarlar.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat[]
### setAFormats(EmfFormat[] value) {#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---}
```
public void setAFormats(EmfFormat[] value)
```


Tercih sırasına göre, EmrFormat nesneleri (bölüm 2.2.4) tarafından belirtilen grafik biçimlerinin CountFormats uzunluğundaki bir dizisini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfFormat\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfformat) |  |

### getFormatData() {#getFormatData--}
```
public byte[][] getFormatData()
```


Bu kayıtta bulunan tüm grafik biçimleri için görüntü verisinin baytlarından oluşan değişken uzunlukta bir dizi alır veya ayarlar. Her bir görüntünün veri boyutu, ilgili EmrFormat nesnesindeki DataSize alanı tarafından sağlanır. Böylece, bu alanın toplam boyutu tüm EmrFormat nesnelerindeki DataSize değerlerinin toplamıdır. Her bir görüntünün grafik biçimi, ilgili EmrFormat nesnesindeki Signature alanı tarafından belirtilir.

**Returns:**
byte[][]
### setFormatData(byte[][] value) {#setFormatData-byte-----}
```
public void setFormatData(byte[][] value)
```


Bu kayıtta bulunan tüm grafik biçimleri için görüntü verisinin baytlarından oluşan değişken uzunlukta bir dizi alır veya ayarlar. Her bir görüntünün veri boyutu, ilgili EmrFormat nesnesindeki DataSize alanı tarafından sağlanır. Böylece, bu alanın toplam boyutu tüm EmrFormat nesnelerindeki DataSize değerlerinin toplamıdır. Her bir görüntünün grafik biçimi, ilgili EmrFormat nesnesindeki Signature alanı tarafından belirtilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[][] |  |

