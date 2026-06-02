---
title: "EmfPolyTextOutA"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_POLYTEXTOUTA kaydı, geçerli yazı tipi ve metin renklerini kullanarak bir veya daha fazla ASCII metin dizesi çizer."
type: docs
weight: 97
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutA extends EmfDrawingRecordType
```

EMR_POLYTEXTOUTA kaydı, mevcut yazı tipi ve metin renklerini kullanarak bir veya daha fazla ASCII metin dizesi çizer.

Çıktı için kullanılan yazı tipi ve metin renkleri, oynatma aygıt bağlamının mevcut durumundaki özelliklerle belirtilir. EMR_POLYTEXTOUTA, bir dize başına bir kayıt olacak şekilde bir dizi EMR_EXTTEXTOUTW kaydı (bölüm 2.3.5.7) ile taklit edilmelidir. Bu, her EmrText nesnesindeki ASCII metin dizesinin Unicode UTF16-LE kodlamasına dönüştürülmesini gerektirir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPolyTextOutA(EmfRecord source)](#EmfPolyTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfPolyTextOutA` sınıfının yeni bir örneğini başlatır. |
| [EmfPolyTextOutA()](#EmfPolyTextOutA--) | [EmfPolyTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta) sınıfının yeni bir örneğini başlatır. |
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
| [getAEmrText()](#getAEmrText--) | Metin öznitelikleri ve boşluk değerleriyle 8 bit ASCII karakterlerinde çıktı dizelerini belirten EmrText nesnelerinin (bölüm 2.2.5) bir dizisini alır veya ayarlar. |
| [setAEmrText(EmfText[] value)](#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | Metin öznitelikleri ve boşluk değerleriyle 8 bit ASCII karakterlerinde çıktı dizelerini belirten EmrText nesnelerinin (bölüm 2.2.5) bir dizisini alır veya ayarlar. |
### EmfPolyTextOutA(EmfRecord source) {#EmfPolyTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutA(EmfRecord source)
```


`EmfPolyTextOutA` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfPolyTextOutA() {#EmfPolyTextOutA--}
```
public EmfPolyTextOutA()
```


[EmfPolyTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta) sınıfının yeni bir örneğini başlatır.

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

### getAEmrText() {#getAEmrText--}
```
public EmfText[] getAEmrText()
```


Metin öznitelikleri ve boşluk değerleriyle 8 bit ASCII karakterlerinde çıktı dizelerini belirten EmrText nesnelerinin (bölüm 2.2.5) bir dizisini alır veya ayarlar. EmrText nesnelerinin sayısı cStrings ile belirtilir.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setAEmrText(EmfText[] value) {#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setAEmrText(EmfText[] value)
```


Metin öznitelikleri ve boşluk değerleriyle 8 bit ASCII karakterlerinde çıktı dizelerini belirten EmrText nesnelerinin (bölüm 2.2.5) bir dizisini alır veya ayarlar. EmrText nesnelerinin sayısı cStrings ile belirtilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

