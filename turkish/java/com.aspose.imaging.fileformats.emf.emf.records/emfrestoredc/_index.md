---
title: "EmfRestoreDc"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_RESTOREDC kaydı, oynatma cihaz bağlamını belirtilen duruma geri yükler."
type: docs
weight: 109
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfRestoreDc extends EmfStateRecordType
```

EMR\_RESTOREDC kaydı, oynatma cihaz bağlamını belirtilen duruma geri yükler. Oynatma cihaz bağlamı, önceki EMR\_SAVEDC kayıtları (bölüm 2.3.11) tarafından oluşturulan bir yığından durum bilgisi çıkarılarak geri yüklenir.

Yığın, oynatma aygıt bağlamının birden fazla örneği için durum bilgisi içerebilir. Bir durum geri yüklendiğinde, daha yeni kaydedilen tüm durum örnekleri MUST atılmalıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfRestoreDc(EmfRecord source)](#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfRestoreDc` sınıfının yeni bir örneğini başlatır. |
| [EmfRestoreDc()](#EmfRestoreDc--) | `EmfRestoreDc` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSavedDc()](#getSavedDc--) | 32 bit işaretli bir tamsayı alır veya ayarlar; bu, mevcut duruma göre geri yüklenecek kaydedilmiş durumu belirtir. |
| [setSavedDc(int value)](#setSavedDc-int-) | 32 bit işaretli bir tamsayı alır veya ayarlar; bu, mevcut duruma göre geri yüklenecek kaydedilmiş durumu belirtir. |
### EmfRestoreDc(EmfRecord source) {#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRestoreDc(EmfRecord source)
```


`EmfRestoreDc` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfRestoreDc() {#EmfRestoreDc--}
```
public EmfRestoreDc()
```


`EmfRestoreDc` sınıfının yeni bir örneğini başlatır.

### getSavedDc() {#getSavedDc--}
```
public int getSavedDc()
```


32 bit işaretli bir tamsayı alır veya ayarlar; bu, mevcut duruma göre geri yüklenecek kaydedilmiş durumu belirtir. Bu değer NEGATİF olmalıdır; \\u20131, yığında en son kaydedilen durumu, \\u20132 ise ondan bir önceki durumu temsil eder, vb.

**Returns:**
int
### setSavedDc(int value) {#setSavedDc-int-}
```
public void setSavedDc(int value)
```


32 bit işaretli bir tamsayı alır veya ayarlar; bu, mevcut duruma göre geri yüklenecek kaydedilmiş durumu belirtir. Bu değer NEGATİF olmalıdır; \\u20131, yığında en son kaydedilen durumu, \\u20132 ise ondan bir önceki durumu temsil eder, vb.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

