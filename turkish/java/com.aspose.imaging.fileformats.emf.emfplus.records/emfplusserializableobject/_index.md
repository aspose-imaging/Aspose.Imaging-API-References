---
title: "EmfPlusSerializableObject"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusSerializableObject kaydı, bir veri tamponuna serileştirilmiş bir görüntü efektleri parametre bloğunu tanımlar."
type: docs
weight: 53
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusSerializableObject extends EmfPlusObjectRecordType
```

EmfPlusSerializableObject kaydı, bir veri tamponuna serileştirilmiş bir görüntü efektleri parametre bloğunu tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusSerializableObject(EmfPlusRecord source)](#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Yeni bir `EmfPlusSerializableObject` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFlags()](#getFlags--) | Alır veya ayarlar kullanılmayan 16 bitlik işaretsiz tam sayıyı. |
| [setFlags(short value)](#setFlags-short-) | Alır veya ayarlar kullanılmayan 16 bitlik işaretsiz tam sayıyı. |
| [getObjectGuid()](#getObjectGuid--) | Görüntü etkisi için GUID paket temsili değerini ([MS-DTYP] bölüm 2.3.4.2) alır veya ayarlar. |
| [setObjectGuid(GuidPacketRepresentation value)](#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) | Görüntü etkisi için GUID paket temsili değerini ([MS-DTYP] bölüm 2.3.4.2) alır veya ayarlar. |
| [getBufferSize()](#getBufferSize--) | 32 bit işaretsiz tamsayıyı alır veya ayarlar; bu, 32 bit hizalı Buffer alanının bayt cinsinden boyutunu belirtir. |
| [setBufferSize(int value)](#setBufferSize-int-) | 32 bit işaretsiz tamsayıyı alır veya ayarlar; bu, 32 bit hizalı Buffer alanının bayt cinsinden boyutunu belirtir. |
| [getBuffer()](#getBuffer--) | ObjectGUID alanındaki GUID ile eşleşen serileştirilmiş görüntü efektleri parametre bloğunu içeren BufferSize baytlık bir dizi alır veya ayarlar. |
| [setBuffer(byte[] value)](#setBuffer-byte---) | ObjectGUID alanındaki GUID ile eşleşen serileştirilmiş görüntü efektleri parametre bloğunu içeren BufferSize baytlık bir dizi alır veya ayarlar. |
| [getImageEffect()](#getImageEffect--) | Görüntü etkisini alır veya ayarlar. |
| [setImageEffect(EmfPlusImageEffectsObjectType value)](#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-) | Görüntü etkisini alır veya ayarlar. |
### EmfPlusSerializableObject(EmfPlusRecord source) {#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSerializableObject(EmfPlusRecord source)
```


Yeni bir `EmfPlusSerializableObject` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Kullanılmayan 16 bit işaretsiz tamsayıyı alır veya ayarlar. Bu alan **SHOULD** sıfır olarak ayarlanmalı ve **MUST** alındığında göz ardı edilmelidir.

Değer: Bayraklar.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Kullanılmayan 16 bit işaretsiz tamsayıyı alır veya ayarlar. Bu alan **SHOULD** sıfır olarak ayarlanmalı ve **MUST** alındığında göz ardı edilmelidir.

Değer: Bayraklar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getObjectGuid() {#getObjectGuid--}
```
public GuidPacketRepresentation getObjectGuid()
```


Görüntü etkisi için GUID paket temsili değerini ([MS-DTYP] bölüm 2.3.4.2) alır veya ayarlar. Bu **MUST** ImageEffects tanımlayıcılarından (bölüm 2.1.3.1) biriyle eşleşmelidir.

**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### setObjectGuid(GuidPacketRepresentation value) {#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void setObjectGuid(GuidPacketRepresentation value)
```


Görüntü etkisi için GUID paket temsili değerini ([MS-DTYP] bölüm 2.3.4.2) alır veya ayarlar. Bu **MUST** ImageEffects tanımlayıcılarından (bölüm 2.1.3.1) biriyle eşleşmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### getBufferSize() {#getBufferSize--}
```
public int getBufferSize()
```


32 bit işaretsiz tamsayıyı alır veya ayarlar; bu, 32 bit hizalı Buffer alanının bayt cinsinden boyutunu belirtir.

**Returns:**
int
### setBufferSize(int value) {#setBufferSize-int-}
```
public void setBufferSize(int value)
```


32 bit işaretsiz tamsayıyı alır veya ayarlar; bu, 32 bit hizalı Buffer alanının bayt cinsinden boyutunu belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBuffer() {#getBuffer--}
```
public byte[] getBuffer()
```


ObjectGUID alanındaki GUID ile eşleşen serileştirilmiş görüntü efektleri parametre bloğunu içeren BufferSize baytlık bir dizi alır veya ayarlar. Bu **MUST** Image Effects nesnelerinden (bölüm 2.2.3) biri olmalıdır.

**Returns:**
byte[]
### setBuffer(byte[] value) {#setBuffer-byte---}
```
public void setBuffer(byte[] value)
```


ObjectGUID alanındaki GUID ile eşleşen serileştirilmiş görüntü efektleri parametre bloğunu içeren BufferSize baytlık bir dizi alır veya ayarlar. Bu **MUST** Image Effects nesnelerinden (bölüm 2.2.3) biri olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getImageEffect() {#getImageEffect--}
```
public EmfPlusImageEffectsObjectType getImageEffect()
```


Görüntü etkisini alır veya ayarlar.

Değer: Görüntü etkisi.

**Returns:**
[EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
### setImageEffect(EmfPlusImageEffectsObjectType value) {#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-}
```
public void setImageEffect(EmfPlusImageEffectsObjectType value)
```


Görüntü etkisini alır veya ayarlar.

Değer: Görüntü etkisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype) |  |

