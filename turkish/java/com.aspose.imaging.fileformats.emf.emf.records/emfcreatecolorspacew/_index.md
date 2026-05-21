---
title: "EmfCreateColorSpaceW"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_CREATECOLORSPACEW kaydı, Unicode karakterlerden oluşan bir ada sahip bir renk profili üzerinden mantıksal bir renk alanı nesnesi oluşturur."
type: docs
weight: 37
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpaceW extends EmfObjectCreationRecordType
```

EMR_CREATECOLORSPACEW kaydı, adı Unicode karakterlerinden oluşan bir renk profiliyle mantıksal bir renk uzayı nesnesi oluşturur.

Bu kayıt tarafından tanımlanan mantıksal renk uzayı nesnesi, sonraki grafik işlemlerinde kullanılacak mantıksal renk uzayını tanımlayan bir EMR\\_SETCOLORSPACE kaydı (bölüm 2.3.8.7) aracılığıyla oynatma aygıtı bağlamına seçilebilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfCreateColorSpaceW(EmfRecord source)](#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfCreateColorSpaceW` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhCS()](#getIhCS--) | EMF nesne tablosundaki (bölüm 3.1.1.1) mantıksal renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [setIhCS(int value)](#setIhCS-int-) | EMF nesne tablosundaki (bölüm 3.1.1.1) mantıksal renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [getLcs()](#getLcs--) | WMF LogColorSpaceW nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.12) ve bu nesne Unicode UTF16-LE karakterlerinde bir renk profili adını belirtebilir. |
| [setLcs(WmfLogColorSpaceW value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-) | WMF LogColorSpaceW nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.12) ve bu nesne Unicode UTF16-LE karakterlerinde bir renk profili adını belirtebilir. |
| [getDwFlags()](#getDwFlags--) | Bu kayıttaki veriler hakkında bilgi sağlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setDwFlags(int value)](#setDwFlags-int-) | Bu kayıttaki veriler hakkında bilgi sağlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getCbData()](#getCbData--) | Data alanının bayt cinsinden boyutunu belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. |
| [setCbData(int value)](#setCbData-int-) | Data alanının bayt cinsinden boyutunu belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. |
| [getData()](#getData--) | Renk profili verilerini belirten isteğe bağlı bir bayt dizisini alır veya ayarlar. |
| [setData(byte[] value)](#setData-byte---) | Renk profili verilerini belirten isteğe bağlı bir bayt dizisini alır veya ayarlar. |
### EmfCreateColorSpaceW(EmfRecord source) {#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpaceW(EmfRecord source)
```


`EmfCreateColorSpaceW` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


EMF nesne tablosundaki (bölüm 3.1.1.1) mantıksal renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


EMF nesne tablosundaki (bölüm 3.1.1.1) mantıksal renk uzayı nesnesinin dizinini belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLcs() {#getLcs--}
```
public WmfLogColorSpaceW getLcs()
```


WMF LogColorSpaceW nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.12) ve bu nesne Unicode UTF16-LE karakterlerinde bir renk profili adını belirtebilir.

**Returns:**
[WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew)
### setLcs(WmfLogColorSpaceW value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-}
```
public void setLcs(WmfLogColorSpaceW value)
```


WMF LogColorSpaceW nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.12) ve bu nesne Unicode UTF16-LE karakterlerinde bir renk profili adını belirtebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew) |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Bu kayıttaki veriler hakkında bilgi sağlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Bu kayıttaki veriler hakkında bilgi sağlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Data alanının bayt cinsinden boyutunu belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Data alanının bayt cinsinden boyutunu belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Renk profili verilerini belirten isteğe bağlı bir bayt dizisini alır veya ayarlar.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Renk profili verilerini belirten isteğe bağlı bir bayt dizisini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

