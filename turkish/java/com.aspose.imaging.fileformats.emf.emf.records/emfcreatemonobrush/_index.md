---
title: "EmfCreateMonoBrush"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_CREATEMONOBRUSH kaydı grafik işlemleri için tek renkli bir desen fırçası tanımlar."
type: docs
weight: 39
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateMonoBrush extends EmfObjectCreationRecordType
```

EMR\_CREATEMONOBRUSH kaydı grafik işlemleri için tek renkli bir desen fırçası tanımlar. Desen, tek renkli bir DIB ile belirtilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfCreateMonoBrush(EmfRecord source)](#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfCreateMonoBrush` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | 32 bit işaretsiz tamsayıyı alır veya ayarlar; bu tamsayı EMF Nesne Tablosundaki (bölüm 3.1.1.1) monokrom desen fırça nesnesinin dizinini belirtir. |
| [setIhBrush(int value)](#setIhBrush-int-) | 32 bit işaretsiz tamsayıyı alır veya ayarlar; bu tamsayı EMF Nesne Tablosundaki (bölüm 3.1.1.1) monokrom desen fırça nesnesinin dizinini belirtir. |
| [getUsage()](#getUsage--) | DIB başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setUsage(int value)](#setUsage-int-) | DIB başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getBitmapBuffer()](#getBitmapBuffer--) | [MS-WMF] bölüm 2.2.2.9'da belirtilen WMF DeviceIndependentBitmap nesnesi biçiminde paketlenmiş bir DIB içeren tamponu alır veya ayarlar. |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | [MS-WMF] bölüm 2.2.2.9'da belirtilen WMF DeviceIndependentBitmap nesnesi biçiminde paketlenmiş bir DIB içeren tamponu alır veya ayarlar. |
### EmfCreateMonoBrush(EmfRecord source) {#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateMonoBrush(EmfRecord source)
```


Yeni bir `EmfCreateMonoBrush` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


32 bit işaretsiz tamsayıyı alır veya ayarlar; bu tamsayı EMF Nesne Tablosundaki (bölüm 3.1.1.1) monokrom desen fırça nesnesinin dizinini belirtir. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


32 bit işaretsiz tamsayıyı alır veya ayarlar; bu tamsayı EMF Nesne Tablosundaki (bölüm 3.1.1.1) monokrom desen fırça nesnesinin dizinini belirtir. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

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

