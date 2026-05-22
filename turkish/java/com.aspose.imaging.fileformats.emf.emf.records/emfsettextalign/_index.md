---
title: "EmfSetTextAlign"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SETTEXTALIGN kaydı, metin hizalamasını belirtir."
type: docs
weight: 139
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextAlign extends EmfStateRecordType
```

EMR\_SETTEXTALIGN kaydı, metin hizalamasını belirtir.

EMR\_SMALLTEXTOUT, EMR\_EXTTEXTOUTA ve EMR\_EXTTEXTOUTW kayıtları, çıktı ortamında bir metin dizesini konumlandırmak için metin hizalama değerlerini kullanır. Bu değerler, bir referans noktası ile metni sınırlayan dikdörtgen arasındaki ilişkiyi tanımlar. Referans noktası ya mevcut konum ya da bir metin çıkış kaydına geçirilen bir noktadır. Metni sınırlayan dikdörtgen, metin dizesindeki karakter hücreleriyle oluşur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSetTextAlign(EmfRecord source)](#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfSetTextAlign` sınıfı örneği başlatır. |
| [EmfSetTextAlign()](#EmfSetTextAlign--) | Yeni bir `EmfSetTextAlign` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTextAlignmentMode()](#getTextAlignmentMode--) | Metin hizalama bayrakları maskesi kullanarak metin hizalamasını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setTextAlignmentMode(int value)](#setTextAlignmentMode-int-) | Metin hizalama bayrakları maskesi kullanarak metin hizalamasını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
### EmfSetTextAlign(EmfRecord source) {#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextAlign(EmfRecord source)
```


Yeni bir `EmfSetTextAlign` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfSetTextAlign() {#EmfSetTextAlign--}
```
public EmfSetTextAlign()
```


Yeni bir `EmfSetTextAlign` sınıfı örneği başlatır.

### getTextAlignmentMode() {#getTextAlignmentMode--}
```
public int getTextAlignmentMode()
```


Metin hizalama bayrakları maskesi kullanarak metin hizalamasını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değerler, yatay temel çizgiye sahip metin için `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] bölüm 2.1.2.3) veya dikey temel çizgiye sahip metin için `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] bölüm 2.1.2.4) olabilir. Yatay ve dikey hizalamayı etkileyenlerden yalnızca bir değer seçilebilir.

**Returns:**
int
### setTextAlignmentMode(int value) {#setTextAlignmentMode-int-}
```
public void setTextAlignmentMode(int value)
```


Metin hizalama bayrakları maskesi kullanarak metin hizalamasını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değerler, yatay temel çizgiye sahip metin için `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] bölüm 2.1.2.3) veya dikey temel çizgiye sahip metin için `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] bölüm 2.1.2.4) olabilir. Yatay ve dikey hizalamayı etkileyenlerden yalnızca bir değer seçilebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

