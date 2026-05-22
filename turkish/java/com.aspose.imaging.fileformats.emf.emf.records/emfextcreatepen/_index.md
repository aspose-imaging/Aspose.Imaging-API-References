---
title: "EmfExtCreatePen"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_EXTCREATEPEN kaydı, grafik işlemleri için genişletilmiş bir mantıksal kalem tanımlar."
type: docs
weight: 52
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreatePen extends EmfObjectCreationRecordType
```

EMR\\_EXTCREATEPEN kaydı, grafik işlemleri için genişletilmiş bir mantıksal kalem tanımlar. Çizgi stili olarak kullanılmak üzere isteğe bağlı bir DIB belirtilebilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfExtCreatePen(EmfRecord record)](#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfExtCreatePen` sınıfının yeni bir örneğini başlatır. |
| [EmfExtCreatePen()](#EmfExtCreatePen--) | `EmfExtCreatePen` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhPen()](#getIhPen--) | Genişletilmiş mantıksal kalem nesnesinin EMF Nesne Tablosundaki (bölüm 3.1.1.1) dizinini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setIhPen(int value)](#setIhPen-int-) | Genişletilmiş mantıksal kalem nesnesinin EMF Nesne Tablosundaki (bölüm 3.1.1.1) dizinini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getElp()](#getElp--) | Opsiyonel bir çizgi stili dizisi dahil olmak üzere niteliklere sahip genişletilmiş mantıksal kalemi belirten bir LogPenEx nesnesini (bölüm 2.2.20) alır veya ayarlar. |
| [setElp(EmfLogPenEx value)](#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-) | Opsiyonel bir çizgi stili dizisi dahil olmak üzere niteliklere sahip genişletilmiş mantıksal kalemi belirten bir LogPenEx nesnesini (bölüm 2.2.20) alır veya ayarlar. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Bir WMF DeviceIndependentBitmap nesnesi ([MS-WMF] bölüm 2.2.2.9) biçiminde paketlenmiş bir DIB içeren opsiyonel bir tamponu alır veya ayarlar. |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Bir WMF DeviceIndependentBitmap nesnesi ([MS-WMF] bölüm 2.2.2.9) biçiminde paketlenmiş bir DIB içeren opsiyonel bir tamponu alır veya ayarlar. |
### EmfExtCreatePen(EmfRecord record) {#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreatePen(EmfRecord record)
```


`EmfExtCreatePen` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kayıt. |

### EmfExtCreatePen() {#EmfExtCreatePen--}
```
public EmfExtCreatePen()
```


`EmfExtCreatePen` sınıfının yeni bir örneğini başlatır.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


EMF Nesne Tablosundaki (bölüm 3.1.1.1) genişletilmiş mantıksal kalem nesnesinin dizinini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


EMF Nesne Tablosundaki (bölüm 3.1.1.1) genişletilmiş mantıksal kalem nesnesinin dizinini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getElp() {#getElp--}
```
public EmfLogPenEx getElp()
```


Opsiyonel bir çizgi stili dizisi dahil olmak üzere niteliklere sahip genişletilmiş mantıksal kalemi belirten bir LogPenEx nesnesini (bölüm 2.2.20) alır veya ayarlar.

**Returns:**
[EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex)
### setElp(EmfLogPenEx value) {#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-}
```
public void setElp(EmfLogPenEx value)
```


Opsiyonel bir çizgi stili dizisi dahil olmak üzere niteliklere sahip genişletilmiş mantıksal kalemi belirten bir LogPenEx nesnesini (bölüm 2.2.20) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex) |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Bir WMF DeviceIndependentBitmap nesnesi ([MS-WMF] bölüm 2.2.2.9) biçiminde paketlenmiş bir DIB içeren opsiyonel bir tamponu alır veya ayarlar. Bu tamponun EMR\\_EXTCREATEPEN kaydının sabit kısmı ile bitişik olması gerekmez.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Bir WMF DeviceIndependentBitmap nesnesi ([MS-WMF] bölüm 2.2.2.9) biçiminde paketlenmiş bir DIB içeren opsiyonel bir tamponu alır veya ayarlar. Bu tamponun EMR\\_EXTCREATEPEN kaydının sabit kısmı ile bitişik olması gerekmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

