---
title: "EmfRoundRect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_ROUNDRECT kaydı, yuvarlatılmış köşelere sahip bir dikdörtgen belirtir."
type: docs
weight: 111
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRoundRect extends EmfDrawingRecordType
```

EMR\\_ROUNDRECT kaydı, yuvarlatılmış köşelere sahip bir dikdörtgen belirtir. Dikdörtgen, mevcut kalem kullanılarak kenar çizilir ve mevcut fırça kullanılarak doldurulur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfRoundRect(EmfRecord source)](#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfRoundRect` sınıfının yeni bir örneğini başlatır. |
| [EmfRoundRect()](#EmfRoundRect--) | Yeni bir [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBox()](#getBox--) | Çizilecek kapsayıcı- kapsayıcı dikdörtgeni belirten, [MS-WMF] bölüm 2.2.2.19'da tanımlanan 128-bit WMF RectL nesnesini alır veya ayarlar. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Çizilecek kapsayıcı- kapsayıcı dikdörtgeni belirten, [MS-WMF] bölüm 2.2.2.19'da tanımlanan 128-bit WMF RectL nesnesini alır veya ayarlar. |
| [getCorner()](#getCorner--) | Yuvarlatılmış köşeleri çizmeye kullanılan elipsin mantıksal koordinatlardaki genişlik ve yüksekliğini belirten, [MS-WMF] bölüm 2.2.2.22'de tanımlanan 64-bit WMF SizeL nesnesini alır veya ayarlar. |
| [setCorner(Size value)](#setCorner-com.aspose.imaging.Size-) | Yuvarlatılmış köşeleri çizmeye kullanılan elipsin mantıksal koordinatlardaki genişlik ve yüksekliğini belirten, [MS-WMF] bölüm 2.2.2.22'de tanımlanan 64-bit WMF SizeL nesnesini alır veya ayarlar. |
### EmfRoundRect(EmfRecord source) {#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRoundRect(EmfRecord source)
```


`EmfRoundRect` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfRoundRect() {#EmfRoundRect--}
```
public EmfRoundRect()
```


Yeni bir [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect) sınıfı örneği başlatır.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Çizilecek kapsayıcı- kapsayıcı dikdörtgeni belirten, [MS-WMF] bölüm 2.2.2.19'da tanımlanan 128-bit WMF RectL nesnesini alır veya ayarlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Çizilecek kapsayıcı- kapsayıcı dikdörtgeni belirten, [MS-WMF] bölüm 2.2.2.19'da tanımlanan 128-bit WMF RectL nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCorner() {#getCorner--}
```
public Size getCorner()
```


Yuvarlatılmış köşeleri çizmeye kullanılan elipsin mantıksal koordinatlardaki genişlik ve yüksekliğini belirten, [MS-WMF] bölüm 2.2.2.22'de tanımlanan 64-bit WMF SizeL nesnesini alır veya ayarlar.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setCorner(Size value) {#setCorner-com.aspose.imaging.Size-}
```
public void setCorner(Size value)
```


Yuvarlatılmış köşeleri çizmeye kullanılan elipsin mantıksal koordinatlardaki genişlik ve yüksekliğini belirten, [MS-WMF] bölüm 2.2.2.22'de tanımlanan 64-bit WMF SizeL nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

