---
title: "EmfPlusDrawImagePoints"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusDrawImagePoints kaydı bir paralelkenar içinde ölçeklenmiş bir görüntü çizmeyi belirtir."
type: docs
weight: 23
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImagePoints extends EmfPlusDrawingRecordType
```

EmfPlusDrawImagePoints kaydı bir paralelkenar içinde ölçeklenmiş bir görüntü çizmeyi belirtir.

Bir EmfPlusImage, bir bitmap veya metafile belirtebilir. Bir görüntüdeki renkler, renderleme sırasında değiştirilebilir. Düzeltilebilir, karartılabilir, aydınlatılabilir ve kaldırılabilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusDrawImagePoints(EmfPlusRecord source)](#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusDrawImagePoints` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCompressed()](#getCompressed--) | PointData'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | PointData'ın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır veya ayarlar. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını alır veya ayarlar. |
| [getApplyingAnEffect()](#getApplyingAnEffect--) | Bir etki uygulanıp uygulanmadığını gösteren bir değeri alır veya ayarlar. |
| [setApplyingAnEffect(boolean value)](#setApplyingAnEffect-boolean-) | Bir etki uygulanıp uygulanmadığını gösteren bir değeri alır veya ayarlar. |
| [getRelative()](#getRelative--) | Bu `EmfPlusDrawImagePoints` öğesinin göreli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setRelative(boolean value)](#setRelative-boolean-) | Bu `EmfPlusDrawImagePoints` öğesinin göreli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getImageAttributesId()](#getImageAttributesId--) | EMF+ Nesne Tablosunda isteğe bağlı EmfPlusImageAttributes nesnesinin (bölüm 2.2.1.5) dizinini içeren 32 bit işaretsiz bir tam sayı alır veya ayarlar. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | EMF+ Nesne Tablosunda isteğe bağlı EmfPlusImageAttributes nesnesinin (bölüm 2.2.1.5) dizinini içeren 32 bit işaretsiz bir tam sayı alır veya ayarlar. |
| [getSrcUnit()](#getSrcUnit--) | SrcRect alanının birimlerini tanımlayan 32 bit işaretli bir tam sayı alır veya ayarlar. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | SrcRect alanının birimlerini tanımlayan 32 bit işaretli bir tam sayı alır veya ayarlar. |
| [getSrcRect()](#getSrcRect--) | Renderlenecek görüntünün bir bölümünü tanımlayan bir EmfPlusRectF nesnesini (bölüm 2.2.2.39) alır veya ayarlar. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Renderlenecek görüntünün bir bölümünü tanımlayan bir EmfPlusRectF nesnesini (bölüm 2.2.2.39) alır veya ayarlar. |
| [getPointData()](#getPointData--) | Bir paralelkenarın üç noktasını belirten Count noktalarından oluşan bir dizi alır veya ayarlar. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Bir paralelkenarın üç noktasını belirten Count noktalarından oluşan bir dizi alır veya ayarlar. |
### EmfPlusDrawImagePoints(EmfPlusRecord source) {#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImagePoints(EmfPlusRecord source)
```


`EmfPlusDrawImagePoints` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


PointData'nın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. Bu bit, PointData alanının sıkıştırılmış veri belirttiğini gösterir. Ayarlıysa, PointData koordinat uzayında mutlak konumları 16 bit tam sayı koordinatlarıyla belirtir. Temizse, PointData koordinat uzayında mutlak konumları 32 bit kayan nokta koordinatlarıyla belirtir. Not: Aşağıdaki P bayrağı ayarlıysa, bu bayrak tanımsızdır ve YOK SAYILMALIDIR.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


PointData'nın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar. Bu bit, PointData alanının sıkıştırılmış veri belirttiğini gösterir. Ayarlıysa, PointData koordinat uzayında mutlak konumları 16 bit tam sayı koordinatlarıyla belirtir. Temizse, PointData koordinat uzayında mutlak konumları 32 bit kayan nokta koordinatlarıyla belirtir. Not: Aşağıdaki P bayrağı ayarlıysa, bu bayrak tanımsızdır ve YOK SAYILMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Nesne tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosundaki bir EmfPlusImage nesnesinin (bölüm 2.2.1.4) dizini, renderlenecek görüntüyü belirtir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosundaki bir EmfPlusImage nesnesinin (bölüm 2.2.1.4) dizini, renderlenecek görüntüyü belirtir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getApplyingAnEffect() {#getApplyingAnEffect--}
```
public boolean getApplyingAnEffect()
```


Bir değeri alır veya ayarlar; bu değer [applying an effect] olup olmadığını gösterir. Bu bit, görüntünün işlenmesinin bir etki uygulanmasını içerdiğini gösterir. Ayarlanmışsa, Effect sınıfının bir nesnesi daha önceki bir EmfPlusSerializableObject kaydında (bölüm 2.3.5.2) belirtilmiş olmalıdır.

Değer: `true` eğer [applying an effect]; aksi takdirde, `false`.

**Returns:**
boolean
### setApplyingAnEffect(boolean value) {#setApplyingAnEffect-boolean-}
```
public void setApplyingAnEffect(boolean value)
```


Bir değeri alır veya ayarlar; bu değer [applying an effect] olup olmadığını gösterir. Bu bit, görüntünün işlenmesinin bir etki uygulanmasını içerdiğini gösterir. Ayarlanmışsa, Effect sınıfının bir nesnesi daha önceki bir EmfPlusSerializableObject kaydında (bölüm 2.3.5.2) belirtilmiş olmalıdır.

Değer: `true` eğer [applying an effect]; aksi takdirde, `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Bu `EmfPlusDrawImagePoints` öğesinin göreli olup olmadığını gösteren bir değeri alır veya ayarlar. Bu bit, PointData alanının göreli mi yoksa mutlak konumları mı belirttiğini gösterir. Ayarlanmışsa, PointData içindeki her öğe, dizideki bir önceki öğe tarafından belirtilen konuma göre koordinat uzayında bir konum belirtir. PointData'daki ilk öğe durumunda, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir. Not: Bu bayrak ayarlanmışsa, yukarıdaki C bayrağı tanımsızdır ve YOK EDİLMELİDİR.

Değer: göreceli ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Bu `EmfPlusDrawImagePoints` öğesinin göreli olup olmadığını gösteren bir değeri alır veya ayarlar. Bu bit, PointData alanının göreli mi yoksa mutlak konumları mı belirttiğini gösterir. Ayarlanmışsa, PointData içindeki her öğe, dizideki bir önceki öğe tarafından belirtilen konuma göre koordinat uzayında bir konum belirtir. PointData'daki ilk öğe durumunda, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir. Not: Bu bayrak ayarlanmışsa, yukarıdaki C bayrağı tanımsızdır ve YOK EDİLMELİDİR.

Değer: göreceli ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


EMF+ Nesne Tablosunda isteğe bağlı EmfPlusImageAttributes nesnesinin (bölüm 2.2.1.5) dizinini içeren 32 bit işaretsiz bir tam sayı alır veya ayarlar.

Değer: Görüntü öznitelikleri tanımlayıcısı.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


EMF+ Nesne Tablosunda isteğe bağlı EmfPlusImageAttributes nesnesinin (bölüm 2.2.1.5) dizinini içeren 32 bit işaretsiz bir tam sayı alır veya ayarlar.

Değer: Görüntü öznitelikleri tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


SrcRect alanının birimlerini tanımlayan 32 bit işaretli bir tam sayı alır veya ayarlar. Bu, UnitType sayımının UnitPixel değeri olmalıdır (bölüm 2.1.1.33).

Değer: Kaynak birim.

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


SrcRect alanının birimlerini tanımlayan 32 bit işaretli bir tam sayı alır veya ayarlar. Bu, UnitType sayımının UnitPixel değeri olmalıdır (bölüm 2.1.1.33).

Değer: Kaynak birim.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Renderlenecek görüntünün bir bölümünü tanımlayan bir EmfPlusRectF nesnesini (bölüm 2.2.2.39) alır veya ayarlar.

Değer: Kaynak dikdörtgen.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Renderlenecek görüntünün bir bölümünü tanımlayan bir EmfPlusRectF nesnesini (bölüm 2.2.2.39) alır veya ayarlar.

Değer: Kaynak dikdörtgen.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Paralelkenarın üç noktasını belirten Count noktasından oluşan bir dizi alır veya ayarlar. Bu üç nokta, paralelkenarın sol üst, sağ üst ve sol alt köşelerini temsil eder. Paralelkenarın dördüncü noktası ilk üç noktadan türetilir. SrcRect alanı tarafından belirtilen görüntü bölümü, paralelkenarın içine sığması için gerekirse ölçekleme ve kaydırma dönüşümleri uygulanmalıdır.

Değer: Nokta verisi.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Paralelkenarın üç noktasını belirten Count noktasından oluşan bir dizi alır veya ayarlar. Bu üç nokta, paralelkenarın sol üst, sağ üst ve sol alt köşelerini temsil eder. Paralelkenarın dördüncü noktası ilk üç noktadan türetilir. SrcRect alanı tarafından belirtilen görüntü bölümü, paralelkenarın içine sığması için gerekirse ölçekleme ve kaydırma dönüşümleri uygulanmalıdır.

Değer: Nokta verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

