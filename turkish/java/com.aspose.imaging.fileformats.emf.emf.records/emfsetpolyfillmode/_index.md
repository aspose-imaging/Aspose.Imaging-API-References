---
title: "EmfSetPolyFillMode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SETPOLYFILLMODE kaydı, çokgen doldurma modunu tanımlar."
type: docs
weight: 136
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetPolyFillMode extends EmfStateRecordType
```

EMR\_SETPOLYFILLMODE kaydı, çokgen doldurma modunu tanımlar.

Genel olarak, modlar yalnızca karmaşık, üst üste binen bir çokgenin DOLDURULMASI GEREKTİĞİ durumlarda farklılık gösterir; örneğin, merkezinde bir beşgen bulunan beş köşeli bir çokgen, beş uçlu bir yıldız oluşturur. Böyle durumlarda, ALTERNATE modu çokgenin (yıldızın uçları) içindeki her diğer kapalı bölgeyi doldurmalı, ancak WINDING modu tüm bölgeleri (yıldızın uçları ve beşgeni) doldurmalıdır. Doldurma modu ALTERNATE olduğunda, her tarama satırındaki tek numaralı ve çift numaralı çokgen kenarları arasındaki alan doldurulmalıdır. Yani, birinci ve ikinci kenar arasındaki alan, üçüncü ve dördüncü kenar arasındaki alan vb. doldurulmalıdır. Doldurma modu WINDING olduğunda, sıfır olmayan bir winding değerine sahip herhangi bir bölge doldurulmalıdır. Winding değeri, çokgeni çizen kalemin bölge etrafında kaç kez döneceğini gösterir. Çokgenin her bir kenarının yönü önemlidir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSetPolyFillMode(EmfRecord source)](#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfSetPolyFillMode` sınıfının yeni bir örneğini başlatır. |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode--) | `EmfSetPolyFillMode` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPolygonFillMode()](#getPolygonFillMode--) | Çokgen doldurma modunu belirten ve PolygonFillMode (bölüm 2.1.27) numaralandırmasında OLMAK ZORUNDADIR 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setPolygonFillMode(int value)](#setPolygonFillMode-int-) | Çokgen doldurma modunu belirten ve PolygonFillMode (bölüm 2.1.27) numaralandırmasında OLMAK ZORUNDADIR 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
### EmfSetPolyFillMode(EmfRecord source) {#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPolyFillMode(EmfRecord source)
```


`EmfSetPolyFillMode` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfSetPolyFillMode() {#EmfSetPolyFillMode--}
```
public EmfSetPolyFillMode()
```


`EmfSetPolyFillMode` sınıfının yeni bir örneğini başlatır.

### getPolygonFillMode() {#getPolygonFillMode--}
```
public int getPolygonFillMode()
```


Çokgen doldurma modunu belirten ve PolygonFillMode (bölüm 2.1.27) numaralandırmasında OLMAK ZORUNDADIR 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setPolygonFillMode(int value) {#setPolygonFillMode-int-}
```
public void setPolygonFillMode(int value)
```


Çokgen doldurma modunu belirten ve PolygonFillMode (bölüm 2.1.27) numaralandırmasında OLMAK ZORUNDADIR 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

