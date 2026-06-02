---
title: "EmfSaveDc"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Önceki EMR_SAVEDC kayıtları tarafından kaydedilen durum yığınına, varsa, oynatma aygıt bağlamının mevcut durumunu kaydeder."
type: docs
weight: 112
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSaveDc extends EmfStateRecordType
```

Önceki EMR\_SAVEDC kayıtları tarafından kaydedilen durum yığınına, varsa, oynatma aygıt bağlamının mevcut durumunu kaydeder. Durum, şu anda seçili bitmap, fırça, palet, yazı tipi, kalem ve bölge dahil olmak üzere grafik özellikleri ve nesnelerinden oluşur. Durumu geri yüklemek için bir EMR\_RESTOREDC kaydı kullanılır. Bu EMF kaydı hiçbir parametre belirtmez.

Yığın, oynatma aygıt bağlamının birden fazla örneği için durum bilgisi içerebilir. Bir durum geri yüklendiğinde, daha yeni kaydedilen tüm durum örnekleri MUST atılmalıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSaveDc(EmfRecord source)](#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfSaveDc` sınıfının yeni bir örneğini başlatır. |
| [EmfSaveDc()](#EmfSaveDc--) | `EmfSaveDc` sınıfının yeni bir örneğini başlatır. |
### EmfSaveDc(EmfRecord source) {#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSaveDc(EmfRecord source)
```


`EmfSaveDc` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfSaveDc() {#EmfSaveDc--}
```
public EmfSaveDc()
```


`EmfSaveDc` sınıfının yeni bir örneğini başlatır.

