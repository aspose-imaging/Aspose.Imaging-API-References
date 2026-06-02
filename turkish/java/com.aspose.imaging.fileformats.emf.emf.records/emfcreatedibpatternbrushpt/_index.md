---
title: "EmfCreateDibPatternBrushPt"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_CREATEDIBPATTERNBRUSHPT kaydı grafik işlemleri için bir desen fırçası tanımlar."
type: docs
weight: 38
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateDibPatternBrushPt extends EmfObjectCreationRecordType
```

EMR\_CREATEDIBPATTERNBRUSHPT kaydı grafik işlemleri için bir desen fırçası tanımlar. Desen, bir DIB tarafından belirtilir.

Bu kayıt tarafından tanımlanan desen fırça nesnesi, sonraki grafik işlemlerinde kullanılacak desen fırçasını belirten bir EMR\_SELECTOBJECT kaydı (bölüm 2.3.8.5) ile oynatma aygıt bağlamına seçilebilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfCreateDibPatternBrushPt(EmfRecord source)](#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfCreateDibPatternBrushPt` sınıfının yeni bir örneğini başlatır. |
| [EmfCreateDibPatternBrushPt()](#EmfCreateDibPatternBrushPt--) | `EmfCreateDibPatternBrushPt` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | EMF Nesne Tablosunda (bölüm 3.1.1.1) desen fırça nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setIhBrush(int value)](#setIhBrush-int-) | EMF Nesne Tablosunda (bölüm 3.1.1.1) desen fırça nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getUsage()](#getUsage--) | DIB başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setUsage(int value)](#setUsage-int-) | DIB başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getBitmapBuffer()](#getBitmapBuffer--) | [MS-WMF] bölüm 2.2.2.9'da belirtilen WMF DeviceIndependentBitmap nesnesi biçiminde paketlenmiş bir DIB içeren tamponu alır veya ayarlar. |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | [MS-WMF] bölüm 2.2.2.9'da belirtilen WMF DeviceIndependentBitmap nesnesi biçiminde paketlenmiş bir DIB içeren tamponu alır veya ayarlar. |
### EmfCreateDibPatternBrushPt(EmfRecord source) {#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateDibPatternBrushPt(EmfRecord source)
```


`EmfCreateDibPatternBrushPt` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfCreateDibPatternBrushPt() {#EmfCreateDibPatternBrushPt--}
```
public EmfCreateDibPatternBrushPt()
```


`EmfCreateDibPatternBrushPt` sınıfının yeni bir örneğini başlatır.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


EMF Nesne Tablosunda (bölüm 3.1.1.1) desen fırça nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


EMF Nesne Tablosunda (bölüm 3.1.1.1) desen fırça nesnesinin dizinini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getUsage() {#getUsage--}
```
public int getUsage()
```


DIB başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer DIBColors sayımında (bölüm 2.1.9) bulunmalıdır.

**Returns:**
int
### setUsage(int value) {#setUsage-int-}
```
public void setUsage(int value)
```


DIB başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer DIBColors sayımında (bölüm 2.1.9) bulunmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


WMF DeviceIndependentBitmap nesnesi ([MS-WMF] bölüm 2.2.2.9) biçiminde paketlenmiş bir DIB içeren tamponu alır veya ayarlar. EMR\_CREATEDIBPATTERNBRUSHPT kaydının sabit kısmıyla bitişik olması gerekmez.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


WMF DeviceIndependentBitmap nesnesi ([MS-WMF] bölüm 2.2.2.9) biçiminde paketlenmiş bir DIB içeren tamponu alır veya ayarlar. EMR\_CREATEDIBPATTERNBRUSHPT kaydının sabit kısmıyla bitişik olması gerekmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

