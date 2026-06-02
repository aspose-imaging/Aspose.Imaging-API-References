---
title: "EmfFrameRgn"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_FRAMERGN kaydı, belirtilen bölgenin etrafına belirtilen fırça kullanılarak bir kenarlık çizer."
type: docs
weight: 62
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfframergn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFrameRgn extends EmfDrawingRecordType
```

EMR\_FRAMERGN kaydı, belirtilen bölge etrafında belirtilen fırça kullanarak bir kenarlık çizer.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfFrameRgn(EmfRecord source)](#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfFrameRgn` sınıfının örneğini başlatır. |
| [EmfFrameRgn()](#EmfFrameRgn--) | Yeni bir [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | Sınırlayıcı dikdörtgeni belirten, [MS-WMF] bölüm 2.2.2.19'da tanımlanan 128-bit WMF RectL nesnesini alır veya ayarlar. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Sınırlayıcı dikdörtgeni belirten, [MS-WMF] bölüm 2.2.2.19'da tanımlanan 128-bit WMF RectL nesnesini alır veya ayarlar. |
| [getRgnDataSize()](#getRgnDataSize--) | Bölge verisinin boyutunu bayt cinsinden belirten 32 bitlik işaretsiz bir tam sayıyı alır veya ayarlar. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Bölge verisinin boyutunu bayt cinsinden belirten 32 bitlik işaretsiz bir tam sayıyı alır veya ayarlar. |
| [getIhBrush()](#getIhBrush--) | Fırça EMF Nesne Tablosu dizinini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setIhBrush(int value)](#setIhBrush-int-) | Fırça EMF Nesne Tablosu dizinini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getWidth()](#getWidth--) | Mantıksal birimlerde dikey fırça darbesinin genişliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar. |
| [setWidth(int value)](#setWidth-int-) | Mantıksal birimlerde dikey fırça darbesinin genişliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar. |
| [getHeight()](#getHeight--) | Mantıksal birimlerde yatay fırça darbesinin yüksekliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar. |
| [setHeight(int value)](#setHeight-int-) | Mantıksal birimlerde yatay fırça darbesinin yüksekliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar. |
| [getRgnData()](#getRgnData--) | Mantıksal birimlerde bir RegionData nesnesini belirten RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Mantıksal birimlerde bir RegionData nesnesini belirten RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar. |
### EmfFrameRgn(EmfRecord source) {#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFrameRgn(EmfRecord source)
```


Yeni bir `EmfFrameRgn` sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfFrameRgn() {#EmfFrameRgn--}
```
public EmfFrameRgn()
```


Yeni bir [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn) sınıfının örneğini başlatır.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Sınırlayıcı dikdörtgeni belirten, [MS-WMF] bölüm 2.2.2.19'da tanımlanan 128-bit WMF RectL nesnesini alır veya ayarlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Sınırlayıcı dikdörtgeni belirten, [MS-WMF] bölüm 2.2.2.19'da tanımlanan 128-bit WMF RectL nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Bölge verisinin boyutunu bayt cinsinden belirten 32 bitlik işaretsiz bir tam sayıyı alır veya ayarlar.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Bölge verisinin boyutunu bayt cinsinden belirten 32 bitlik işaretsiz bir tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Fırça EMF Nesne Tablosu dizinini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Fırça EMF Nesne Tablosu dizinini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Mantıksal birimlerde dikey fırça darbesinin genişliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Mantıksal birimlerde dikey fırça darbesinin genişliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Mantıksal birimlerde yatay fırça darbesinin yüksekliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Mantıksal birimlerde yatay fırça darbesinin yüksekliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Mantıksal birimlerde bir RegionData nesnesini belirten RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Mantıksal birimlerde bir RegionData nesnesini belirten RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

