---
title: "EmfSetIcmMode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SETICMMODE kaydı, grafik işlemleri için Görüntü Renk Yönetimi (ICM) modunu belirtir."
type: docs
weight: 125
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmMode extends EmfStateRecordType
```

EMR\_SETICMMODE kaydı, grafik işlemleri için Görüntü Renk Yönetimi (ICM) modunu belirtir.

ICM modu etkin olduğunda, EMF kayıtlarında belirtilen renkler RENK EŞLEŞTİRİLMELİDİR, ancak bir bit-blok transferi gerçekleştirildiğinde oynatma cihazı bağlamındaki varsayılan renk profili KULLANILMALIDIR. Varsayılan renk profili istenmiyorsa, bit-blok transferi yapılmadan önce ICM modu KAPATILMALIDIR.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSetIcmMode(EmfRecord source)](#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfSetIcmMode` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIcmMode()](#getIcmMode--) | ICMMode numaralandırmasından (bölüm 2.1.18) ICM'nin etkinleştirilip devre dışı bırakılacağını belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [setIcmMode(int value)](#setIcmMode-int-) | ICMMode numaralandırmasından (bölüm 2.1.18) ICM'nin etkinleştirilip devre dışı bırakılacağını belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. |
### EmfSetIcmMode(EmfRecord source) {#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmMode(EmfRecord source)
```


`EmfSetIcmMode` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getIcmMode() {#getIcmMode--}
```
public int getIcmMode()
```


ICMMode numaralandırmasından (bölüm 2.1.18) ICM'nin etkinleştirilip devre dışı bırakılacağını belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. Bu değer, oynatma cihazı bağlamının durumunun bir parçasıdır.

**Returns:**
int
### setIcmMode(int value) {#setIcmMode-int-}
```
public void setIcmMode(int value)
```


ICMMode numaralandırmasından (bölüm 2.1.18) ICM'nin etkinleştirilip devre dışı bırakılacağını belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. Bu değer, oynatma cihazı bağlamının durumunun bir parçasıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

