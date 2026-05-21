---
title: "EmfPlusObject"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusObject kaydı, grafik işlemlerinde kullanılacak bir nesneyi belirtir."
type: docs
weight: 42
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusObject extends EmfPlusObjectRecordType
```

EmfPlusObject kaydı, grafik işlemlerinde kullanılmak üzere bir nesneyi belirtir. Nesne tanımı birden fazla kayda yayılabilir; bu, Flags alanının değerine göre gösterilir.

EmfPlusObject kaydı geneldir; tüm nesne türleri için kullanılır. Belirli nesne türlerine özgü değerler ObjectData alanında bulunur. Grafik nesnelerinin yönetimi için kavramsal bir model, Managing Graphics Objects (bölüm 3.1.2) içinde açıklanmıştır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusObject(EmfPlusRecord source)](#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusObject` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isContinuable()](#isContinuable--) | Bu örneğin devam edilebilir olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setContinuable(boolean value)](#setContinuable-boolean-) | Bu örneğin devam edilebilir olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getObjectType()](#getObjectType--) | Nesnenin türünü alır veya ayarlar. |
| [setObjectType(byte value)](#setObjectType-byte-) | Nesnenin türünü alır veya ayarlar. |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır veya ayarlar. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını alır veya ayarlar. |
| [getTotalObjectSize()](#getTotalObjectSize--) | Nesnenin toplam boyutunu alır veya ayarlar. |
| [setTotalObjectSize(int value)](#setTotalObjectSize-int-) | Nesnenin toplam boyutunu alır veya ayarlar. |
| [getObjectData()](#getObjectData--) | Flags alanında belirtilen nesne türü için veri içeren bir bayt dizisini alır veya ayarlar. |
| [setObjectData(EmfPlusGraphicsObjectType value)](#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-) | Flags alanında belirtilen nesne türü için veri içeren bir bayt dizisini alır veya ayarlar. |
### EmfPlusObject(EmfPlusRecord source) {#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusObject(EmfPlusRecord source)
```


`EmfPlusObject` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### isContinuable() {#isContinuable--}
```
public boolean isContinuable()
```


Bu örneğin devam edilebilir olup olmadığını gösteren bir değeri alır veya ayarlar. Nesne tanımının bir sonraki EmfPlusObject kaydında devam ettiğini gösterir. Bu bayrak, nesneyi tanımlayan son kayıtta asla ayarlanmaz.

Değer: Bu örnek sıkıştırılmışsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### setContinuable(boolean value) {#setContinuable-boolean-}
```
public void setContinuable(boolean value)
```


Bu örneğin devam edilebilir olup olmadığını gösteren bir değeri alır veya ayarlar. Nesne tanımının bir sonraki EmfPlusObject kaydında devam ettiğini gösterir. Bu bayrak, nesneyi tanımlayan son kayıtta asla ayarlanmaz.

Değer: Bu örnek sıkıştırılmışsa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getObjectType() {#getObjectType--}
```
public byte getObjectType()
```


Nesnenin türünü alır veya ayarlar.

Değer: Nesnenin türü.

**Returns:**
byte
### setObjectType(byte value) {#setObjectType-byte-}
```
public void setObjectType(byte value)
```


Nesnenin türünü alır veya ayarlar.

Değer: Nesnenin türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Nesne tanımlayıcısını alır veya ayarlar. Bu kaydın oluşturduğu nesneyle ilişkilendirilecek EMF+ Nesne Tablosundaki indeksi. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını alır veya ayarlar. Bu kaydın oluşturduğu nesneyle ilişkilendirilecek EMF+ Nesne Tablosundaki indeksi. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getTotalObjectSize() {#getTotalObjectSize--}
```
public int getTotalObjectSize()
```


Nesnenin toplam boyutunu alır veya ayarlar. Kayıt devam edilebilir ise, devam biti ayarlandığında bu alan bulunur. Devam eden nesneler, EmfPlusContineudObjectRecord ile başlayan birden fazla EMF+ kaydına sahiptir. Her EmfPlusContinuedObjectRecord bir TotalObjectSize içerir. TotalObjectSize kadar bayt okunduktan sonra, bir sonraki EMF+ kaydı devam eden nesnenin bir parçası olarak işlenmez.

Değer: Nesnenin toplam boyutu.

**Returns:**
int
### setTotalObjectSize(int value) {#setTotalObjectSize-int-}
```
public void setTotalObjectSize(int value)
```


Nesnenin toplam boyutunu alır veya ayarlar. Kayıt devam edilebilir ise, devam biti ayarlandığında bu alan bulunur. Devam eden nesneler, EmfPlusContineudObjectRecord ile başlayan birden fazla EMF+ kaydına sahiptir. Her EmfPlusContinuedObjectRecord bir TotalObjectSize içerir. TotalObjectSize kadar bayt okunduktan sonra, bir sonraki EMF+ kaydı devam eden nesnenin bir parçası olarak işlenmez.

Değer: Nesnenin toplam boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getObjectData() {#getObjectData--}
```
public EmfPlusGraphicsObjectType getObjectData()
```


Flags alanında belirtilen nesne türü için veri içeren bir bayt dizisini alır veya ayarlar. Verinin içeriği ve biçimi her nesne türü için farklı olabilir. Ek bilgi için bölüm 2.2.1'deki bireysel nesne tanımlarına bakın.

Değer: Nesne verisi.

**Returns:**
[EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
### setObjectData(EmfPlusGraphicsObjectType value) {#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-}
```
public void setObjectData(EmfPlusGraphicsObjectType value)
```


Flags alanında belirtilen nesne türü için veri içeren bir bayt dizisini alır veya ayarlar. Verinin içeriği ve biçimi her nesne türü için farklı olabilir. Ek bilgi için bölüm 2.2.1'deki bireysel nesne tanımlarına bakın.

Değer: Nesne verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype) |  |

