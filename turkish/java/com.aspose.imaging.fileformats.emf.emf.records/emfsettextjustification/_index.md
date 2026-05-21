---
title: "EmfSetTextJustification"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SETTEXTJUSTIFICATION kaydı, metin hizalaması için bölme karakterlerine eklenecek ekstra boşluk miktarını belirtir."
type: docs
weight: 141
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextJustification extends EmfStateRecordType
```

EMR\_SETTEXTJUSTIFICATION kaydı, metin hizalaması için bölme karakterlerine eklenecek ekstra boşluk miktarını belirtir.

EMR\_SETTEXTJUSTIFICATION kaydı kullanmak yerine, bir uygulama bu işlevi gerçekleştirmek için EMR\_EXTTEXTOUTW kaydını (bölüm 2.3.5.8) KULLANMALIdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSetTextJustification(EmfRecord source)](#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfSetTextJustification` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNBreakExtra()](#getNBreakExtra--) | Eklenmek üzere, mantıksal birimlerde, toplam ek alan miktarını belirten 32 bit işaretli bir tam sayı alır veya ayarlar. |
| [setNBreakExtra(int value)](#setNBreakExtra-int-) | Eklenmek üzere, mantıksal birimlerde, toplam ek alan miktarını belirten 32 bit işaretli bir tam sayı alır veya ayarlar. |
| [getNBreakCount()](#getNBreakCount--) | Kesme karakteri sayısını belirten 32 bit işaretli bir tam sayı alır veya ayarlar. |
| [setNBreakCount(int value)](#setNBreakCount-int-) | Kesme karakteri sayısını belirten 32 bit işaretli bir tam sayı alır veya ayarlar. |
### EmfSetTextJustification(EmfRecord source) {#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextJustification(EmfRecord source)
```


`EmfSetTextJustification` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getNBreakExtra() {#getNBreakExtra--}
```
public int getNBreakExtra()
```


Eklenmek üzere, mantıksal birimlerde, toplam ek alan miktarını belirten 32 bit işaretli bir tam sayı alır veya ayarlar.

**Returns:**
int
### setNBreakExtra(int value) {#setNBreakExtra-int-}
```
public void setNBreakExtra(int value)
```


Eklenmek üzere, mantıksal birimlerde, toplam ek alan miktarını belirten 32 bit işaretli bir tam sayı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getNBreakCount() {#getNBreakCount--}
```
public int getNBreakCount()
```


Kesme karakteri sayısını belirten 32 bit işaretli bir tam sayı alır veya ayarlar.

**Returns:**
int
### setNBreakCount(int value) {#setNBreakCount-int-}
```
public void setNBreakCount(int value)
```


Kesme karakteri sayısını belirten 32 bit işaretli bir tam sayı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

