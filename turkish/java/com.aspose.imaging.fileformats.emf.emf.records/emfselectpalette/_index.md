---
title: "EmfSelectPalette"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SELECTPALETTE kaydı, oynatma cihaz bağlamı için mantıksal bir palet tanımlar."
type: docs
weight: 117
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSelectPalette extends EmfObjectManipulationRecordType
```

EMR\_SELECTPALETTE kaydı, oynatma cihaz bağlamı için mantıksal bir palet tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSelectPalette(EmfRecord source)](#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfSelectPalette` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhPal()](#getIhPal--) | 32 bit işaretsiz bir tamsayı alır veya ayarlar; bu, EMF Nesne Tablosundaki bir LogPalette nesnesinin (bölüm 2.2.17) dizinini veya DEFAULT\_PALETTE değerini belirtir; bu değer, StockObject numaralandırmasından (bölüm 2.1.31) bir stok nesne paletinin dizinidir. |
| [setIhPal(int value)](#setIhPal-int-) | 32 bit işaretsiz bir tamsayı alır veya ayarlar; bu, EMF Nesne Tablosundaki bir LogPalette nesnesinin (bölüm 2.2.17) dizinini veya DEFAULT\_PALETTE değerini belirtir; bu değer, StockObject numaralandırmasından (bölüm 2.1.31) bir stok nesne paletinin dizinidir. |
### EmfSelectPalette(EmfRecord source) {#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectPalette(EmfRecord source)
```


`EmfSelectPalette` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


32 bit işaretsiz bir tamsayı alır veya ayarlar; bu, EMF Nesne Tablosundaki bir LogPalette nesnesinin (bölüm 2.2.17) dizinini veya DEFAULT\_PALETTE değerini belirtir; bu değer, StockObject numaralandırmasından (bölüm 2.1.31) bir stok nesne paletinin dizinidir.

Bu değer SIFIR olamaz ve başka bir stok nesnenin dizini olamaz.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


32 bit işaretsiz bir tamsayı alır veya ayarlar; bu, EMF Nesne Tablosundaki bir LogPalette nesnesinin (bölüm 2.2.17) dizinini veya DEFAULT\_PALETTE değerini belirtir; bu değer, StockObject numaralandırmasından (bölüm 2.1.31) bir stok nesne paletinin dizinidir.

Bu değer SIFIR olamaz ve başka bir stok nesnenin dizini olamaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

