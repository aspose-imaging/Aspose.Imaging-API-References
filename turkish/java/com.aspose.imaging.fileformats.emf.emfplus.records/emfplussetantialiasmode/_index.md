---
title: "EmfPlusSetAntiAliasMode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusSetAntiAliasMode kaydı, metin çıktısı için anti-aliasing modunu belirtir."
type: docs
weight: 54
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetAntiAliasMode extends EmfPlusPropertyRecordType
```

EmfPlusSetAntiAliasMode kaydı, metin çıktısı için anti-aliasing modunu belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusSetAntiAliasMode(EmfPlusRecord source)](#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Yeni bir `EmfPlusSetAntiAliasMode` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Düzleştirme modunu alır veya ayarlar. |
| [setSmoothingMode(byte value)](#setSmoothingMode-byte-) | Düzleştirme modunu alır veya ayarlar. |
| [getAntiAliasing()](#getAntiAliasing--) | Anti aliasing [anti aliasing] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Anti aliasing [anti aliasing] olup olmadığını gösteren bir değeri alır veya ayarlar. |
### EmfPlusSetAntiAliasMode(EmfPlusRecord source) {#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetAntiAliasMode(EmfPlusRecord source)
```


Yeni bir `EmfPlusSetAntiAliasMode` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getSmoothingMode() {#getSmoothingMode--}
```
public byte getSmoothingMode()
```


Düzleştirme modunu alır veya ayarlar. (7 bit): SmoothingMode numaralandırmasından (bölüm 2.1.1.28) düzleştirme modu değeri.

Değer: Düzleştirme modu.

**Returns:**
byte
### setSmoothingMode(byte value) {#setSmoothingMode-byte-}
```
public void setSmoothingMode(byte value)
```


Düzleştirme modunu alır veya ayarlar. (7 bit): SmoothingMode numaralandırmasından (bölüm 2.1.1.28) düzleştirme modu değeri.

Değer: Düzleştirme modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getAntiAliasing() {#getAntiAliasing--}
```
public boolean getAntiAliasing()
```


Anti aliasing [anti aliasing] olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, anti-aliasing YAPILMALIdır. Temizse, anti-aliasing YAPILMAMALIDIR.

Değer: `true` eğer [anti aliasing]; aksi takdirde, `false`.

**Returns:**
boolean
### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public void setAntiAliasing(boolean value)
```


Anti aliasing [anti aliasing] olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, anti-aliasing YAPILMALIdır. Temizse, anti-aliasing YAPILMAMALIDIR.

Değer: `true` eğer [anti aliasing]; aksi takdirde, `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

