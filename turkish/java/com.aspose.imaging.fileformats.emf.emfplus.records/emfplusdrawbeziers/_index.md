---
title: "EmfPlusDrawBeziers"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusDrawBeziers kaydı bağlanan Bezier eğrilerinin bir dizisini çizmeyi belirtir."
type: docs
weight: 17
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawBeziers extends EmfPlusDrawingRecordType
```

EmfPlusDrawBeziers kaydı, bir dizi bağlı Bezier eğrisi çizmeyi belirtir. Bezier veri noktalarının sırası başlangıç noktası, kontrol noktası 1, kontrol noktası 2 ve bitiş noktasıdır. Daha fazla bilgi için [MSDN-DrawBeziers] bölümüne bakın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusDrawBeziers(EmfPlusRecord source)](#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusDrawBeziers` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCompressed()](#getCompressed--) | PointData'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | PointData'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [getRelative()](#getRelative--) | PointData'nın göreli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setRelative(boolean value)](#setRelative-boolean-) | PointData'nın göreli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır veya ayarlar. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını alır veya ayarlar. |
| [getPointData()](#getPointData--) | Nokta verisini alır veya ayarlar. Bezier eğrilerinin başlangıç, bitiş ve kontrol noktalarını belirten Count noktasından oluşan bir dizi. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Nokta verisini alır veya ayarlar. Bezier eğrilerinin başlangıç, bitiş ve kontrol noktalarını belirten Count noktasından oluşan bir dizi. |
### EmfPlusDrawBeziers(EmfPlusRecord source) {#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawBeziers(EmfPlusRecord source)
```


`EmfPlusDrawBeziers` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


PointData'nın sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, PointData 16 bit tam sayı koordinatlarıyla koordinat uzayında mutlak konumları belirtir. Temizlenmişse, PointData 32 bit kayan nokta koordinatlarıyla mutlak konumları belirtir. Not: Aşağıdaki Relative bayrağı ayarlanmışsa, bu bayrak tanımsızdır ve YOK EDİLMELİDİR.

Değer: sıkıştırılmışsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


PointData'nın sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, PointData 16 bit tam sayı koordinatlarıyla koordinat uzayında mutlak konumları belirtir. Temizlenmişse, PointData 32 bit kayan nokta koordinatlarıyla mutlak konumları belirtir. Not: Aşağıdaki Relative bayrağı ayarlanmışsa, bu bayrak tanımsızdır ve YOK EDİLMELİDİR.

Değer: sıkıştırılmışsa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


PointData'nın göreli olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, PointData içindeki her öğe, dizideki bir önceki öğe tarafından belirtilen konuma göre koordinat uzayında bir konum belirtir. PointData'daki ilk öğe durumunda, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir. Not: Bu bayrak ayarlanmışsa, yukarıdaki C bayrağı tanımsızdır ve YOK EDİLMELİDİR.

Değer: göreceli ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


PointData'nın göreli olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlanmışsa, PointData içindeki her öğe, dizideki bir önceki öğe tarafından belirtilen konuma göre koordinat uzayında bir konum belirtir. PointData'daki ilk öğe durumunda, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir. Not: Bu bayrak ayarlanmışsa, yukarıdaki C bayrağı tanımsızdır ve YOK EDİLMELİDİR.

Değer: göreceli ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Nesne tanımlayıcısını alır veya ayarlar. Bezier eğrilerini çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) indeksidir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını alır veya ayarlar. Bezier eğrilerini çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) indeksidir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Nokta verisini alır veya ayarlar. Bezier eğrilerinin başlangıç, bitiş ve kontrol noktalarını belirten Count noktasından oluşan bir dizi. Bir Bezier eğrisinin bitiş koordinatı, bir sonraki eğrinin başlangıç koordinatıdır. Kontrol noktaları Bezier etkisini üretmek için kullanılır. Bu dizideki veri tipi Flags alanı tarafından aşağıdaki gibi belirtilir: Veri Tipi Anlamı EmfPlusPointR nesnesi (bölüm 2.2.2.37) Flags içinde P bayrağı ayarlıysa, noktalar göreli konumları belirtir. EmfPlusPointF nesnesi (bölüm 2.2.2.36) Flags alanında P ve C bitleri temizse, noktalar mutlak konumları belirtir. EmfPlusPoint nesnesi (bölüm 2.2.2.35) Flags alanında P biti temiz ve C biti ayarlıysa, noktalar göreli konumları belirtir. Bir Bezier eğrisi kontrol noktalarından geçmez. Kontrol noktaları şu şekilde davranır:

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Nokta verisini alır veya ayarlar. Bezier eğrilerinin başlangıç, bitiş ve kontrol noktalarını belirten Count noktasından oluşan bir dizi. Bir Bezier eğrisinin bitiş koordinatı, bir sonraki eğrinin başlangıç koordinatıdır. Kontrol noktaları Bezier etkisini üretmek için kullanılır. Bu dizideki veri tipi Flags alanı tarafından aşağıdaki gibi belirtilir: Veri Tipi Anlamı EmfPlusPointR nesnesi (bölüm 2.2.2.37) Flags içinde P bayrağı ayarlıysa, noktalar göreli konumları belirtir. EmfPlusPointF nesnesi (bölüm 2.2.2.36) Flags alanında P ve C bitleri temizse, noktalar mutlak konumları belirtir. EmfPlusPoint nesnesi (bölüm 2.2.2.35) Flags alanında P biti temiz ve C biti ayarlıysa, noktalar göreli konumları belirtir. Bir Bezier eğrisi kontrol noktalarından geçmez. Kontrol noktaları şu şekilde davranır:

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

