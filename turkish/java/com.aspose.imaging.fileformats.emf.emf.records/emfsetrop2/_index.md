---
title: "EmfSetRop2"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SETROP2 kaydı, ikili raster işlem modunu tanımlar."
type: docs
weight: 137
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetRop2 extends EmfStateRecordType
```

EMR\_SETROP2 kaydı, ikili raster işlem modunu tanımlar.

İkili raster işlem karışım modları, mevcut kalemle çizerken kaynak ve hedef renklerin nasıl birleştirileceğini tanımlar. Karışım modları, iki değişkenin tüm olası Boolean fonksiyonlarını temsil eden ikili raster işlem kodlarıdır; AND, OR ve XOR (özel OR) ikili işlemleri ve NOT tekli işlemi kullanılır. Karışım modu yalnızca raster cihazlar içindir; vektör cihazlar için mevcut değildir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSetRop2(EmfRecord source)](#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfSetRop2` sınıfının yeni bir örneğini başlatır. |
| [EmfSetRop2()](#EmfSetRop2--) | `EmfSetRop2` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRop2Mode()](#getRop2Mode--) | Raster işlem modunu belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar ve WMF Binary Raster Op enumarasyonunda ([MS-WMF] bölüm 2.1.1.2) yer almalıdır. |
| [setRop2Mode(int value)](#setRop2Mode-int-) | Raster işlem modunu belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar ve WMF Binary Raster Op enumarasyonunda ([MS-WMF] bölüm 2.1.1.2) yer almalıdır. |
### EmfSetRop2(EmfRecord source) {#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetRop2(EmfRecord source)
```


`EmfSetRop2` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfSetRop2() {#EmfSetRop2--}
```
public EmfSetRop2()
```


`EmfSetRop2` sınıfının yeni bir örneğini başlatır.

### getRop2Mode() {#getRop2Mode--}
```
public int getRop2Mode()
```


Raster işlem modunu belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar ve WMF Binary Raster Op enumarasyonunda ([MS-WMF] bölüm 2.1.1.2) yer almalıdır.

**Returns:**
int
### setRop2Mode(int value) {#setRop2Mode-int-}
```
public void setRop2Mode(int value)
```


Raster işlem modunu belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar ve WMF Binary Raster Op enumarasyonunda ([MS-WMF] bölüm 2.1.1.2) yer almalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

