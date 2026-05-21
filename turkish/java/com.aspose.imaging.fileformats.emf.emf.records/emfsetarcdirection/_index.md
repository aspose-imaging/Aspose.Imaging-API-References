---
title: "EmfSetArcDirection"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SETARCDIRECTION kaydı, yay ve dikdörtgen çıktısı için kullanılacak çizim yönünü belirtir."
type: docs
weight: 118
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetArcDirection extends EmfStateRecordType
```

EMR\_SETARCDIRECTION kaydı, yay ve dikdörtgen çıktısı için kullanılacak çizim yönünü tanımlar.

EMR\_SETARCDIRECTION kaydı, aşağıdaki kayıtların çizim yönünü etkiler: - EMR\_ARC (bölüm 2.3.5.2) - EMR\_ARCTO (bölüm 2.3.5.3) - EMR\_CHORD (bölüm 2.3.5.4) - EMR\_ELLIPSE (bölüm 2.3.5.5) - EMR\_PIE (bölüm 2.3.5.15) - EMR\_RECTANGLE (bölüm 2.3.5.34) - EMR\_ROUNDRECT (bölüm 2.3.5.35)
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSetArcDirection(EmfRecord source)](#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfSetArcDirection` sınıfı örneği başlatır. |
| [EmfSetArcDirection()](#EmfSetArcDirection--) | Yeni bir `EmfSetArcDirection` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getArcDirection()](#getArcDirection--) | Yay yönünü belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setArcDirection(int value)](#setArcDirection-int-) | Yay yönünü belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
### EmfSetArcDirection(EmfRecord source) {#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetArcDirection(EmfRecord source)
```


Yeni bir `EmfSetArcDirection` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfSetArcDirection() {#EmfSetArcDirection--}
```
public EmfSetArcDirection()
```


Yeni bir `EmfSetArcDirection` sınıfı örneği başlatır.

### getArcDirection() {#getArcDirection--}
```
public int getArcDirection()
```


Yay yönünü belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. Değer ArcDirection numaralandırmasında (bölüm 2.1.2) olmalıdır. Varsayılan yön saat yönünün tersidir.

**Returns:**
int
### setArcDirection(int value) {#setArcDirection-int-}
```
public void setArcDirection(int value)
```


Yay yönünü belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. Değer ArcDirection numaralandırmasında (bölüm 2.1.2) olmalıdır. Varsayılan yön saat yönünün tersidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

