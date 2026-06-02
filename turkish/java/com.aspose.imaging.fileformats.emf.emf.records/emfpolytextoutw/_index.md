---
title: "EmfPolyTextOutW"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_POLYTEXTOUTW kaydı, mevcut yazı tipi ve metin renklerini kullanarak bir veya daha fazla Unicode metin dizesi çizer."
type: docs
weight: 98
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutW extends EmfDrawingRecordType
```

EMR_POLYTEXTOUTW kaydı, mevcut yazı tipi ve metin renklerini kullanarak bir veya daha fazla Unicode metin dizesi çizer.

Çıktı için kullanılan yazı tipi ve metin renkleri, oynatma aygıtı bağlamının mevcut durumundaki özelliklerle belirtilir. EMR\_POLYTEXTOUTW, her dize için bir EMR\_EXTTEXTOUTW kaydı serisiyle (bölüm 2.3.5.7) taklit edilmelidir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPolyTextOutW(EmfRecord source)](#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfPolyTextOutW` sınıfı örneği başlatır. |
| [EmfPolyTextOutW()](#EmfPolyTextOutW--) | Yeni bir `EmfPolyTextOutW` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | Cihaz birimlerinde sınırlayıcı dikdörtgeni belirten bir WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Cihaz birimlerinde sınırlayıcı dikdörtgeni belirten bir WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). |
| [getIGraphicsMode()](#getIGraphicsMode--) | GraphicsMode sayımından (bölüm 2.1.16) mevcut grafik modunu belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | GraphicsMode sayımından (bölüm 2.1.16) mevcut grafik modunu belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [getExScale()](#getExScale--) | Grafik modu GM_COMPATIBLE ise sayfa birimlerinden .01mm birimlerine X ölçeğini belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [setExScale(float value)](#setExScale-float-) | Grafik modu GM_COMPATIBLE ise sayfa birimlerinden .01mm birimlerine X ölçeğini belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [getEyScale()](#getEyScale--) | Grafik modu GM_COMPATIBLE ise sayfa birimlerinden .01mm birimlerine Y ölçeğini belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [setEyScale(float value)](#setEyScale-float-) | Grafik modu GM_COMPATIBLE ise sayfa birimlerinden .01mm birimlerine Y ölçeğini belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [getWEmrText()](#getWEmrText--) | 16 bit Unicode UTF16-LE karakterlerinde, metin öznitelikleri ve boşluk değerleriyle çıktı dizelerini belirten EmrText nesnelerinin (bölüm 2.2.5) dizisini alır veya ayarlar. |
| [setWEmrText(EmfText[] value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | 16 bit Unicode UTF16-LE karakterlerinde, metin öznitelikleri ve boşluk değerleriyle çıktı dizelerini belirten EmrText nesnelerinin (bölüm 2.2.5) dizisini alır veya ayarlar. |
### EmfPolyTextOutW(EmfRecord source) {#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutW(EmfRecord source)
```


Yeni bir `EmfPolyTextOutW` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfPolyTextOutW() {#EmfPolyTextOutW--}
```
public EmfPolyTextOutW()
```


Yeni bir `EmfPolyTextOutW` sınıfı örneği başlatır.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Cihaz birimlerinde sınırlayıcı dikdörtgeni belirten bir WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19).

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Cihaz birimlerinde sınırlayıcı dikdörtgeni belirten bir WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


GraphicsMode sayımından (bölüm 2.1.16) mevcut grafik modunu belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar.

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


GraphicsMode sayımından (bölüm 2.1.16) mevcut grafik modunu belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Grafik modu GM_COMPATIBLE ise sayfa birimlerinden .01mm birimlerine X ölçeğini belirten 32 bit kayan nokta değerini alır veya ayarlar.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Grafik modu GM_COMPATIBLE ise sayfa birimlerinden .01mm birimlerine X ölçeğini belirten 32 bit kayan nokta değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Grafik modu GM_COMPATIBLE ise sayfa birimlerinden .01mm birimlerine Y ölçeğini belirten 32 bit kayan nokta değerini alır veya ayarlar.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Grafik modu GM_COMPATIBLE ise sayfa birimlerinden .01mm birimlerine Y ölçeğini belirten 32 bit kayan nokta değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getWEmrText() {#getWEmrText--}
```
public EmfText[] getWEmrText()
```


16 bit Unicode UTF16-LE karakterlerinde, metin öznitelikleri ve boşluk değerleriyle çıktı dizelerini belirten EmrText nesnelerinin (bölüm 2.2.5) dizisini alır veya ayarlar. EmrText nesnelerinin sayısı cStrings ile belirtilir.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setWEmrText(EmfText[] value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setWEmrText(EmfText[] value)
```


16 bit Unicode UTF16-LE karakterlerinde, metin öznitelikleri ve boşluk değerleriyle çıktı dizelerini belirten EmrText nesnelerinin (bölüm 2.2.5) dizisini alır veya ayarlar. EmrText nesnelerinin sayısı cStrings ile belirtilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

