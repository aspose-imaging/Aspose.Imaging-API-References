---
title: "EmfExtTextOutA"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_EXTTEXTOUTA kaydı, geçerli yazı tipi ve metin renklerini kullanarak bir ASCII metin dizesi çizer."
type: docs
weight: 56
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtTextOutA extends EmfDrawingRecordType
```

EMR\_EXTTEXTOUTA kaydı, mevcut yazı tipi ve metin renklerini kullanarak bir ASCII metin dizesi çizer.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfExtTextOutA(EmfRecord source)](#EmfExtTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfExtTextOutA` sınıfı örneği başlatır. |
| [EmfExtTextOutA()](#EmfExtTextOutA--) | Yeni bir [EmfExtTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). |
| [getIGraphicsMode()](#getIGraphicsMode--) | GraphicsMode numaralandırmasından (bölüm 2.1.16) grafik modunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | GraphicsMode numaralandırmasından (bölüm 2.1.16) grafik modunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getExScale()](#getExScale--) | X ekseni boyunca uygulanacak ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar; bu faktör sayfa uzayı birimlerinden .01mm birimlerine dönüştürür. |
| [setExScale(float value)](#setExScale-float-) | X ekseni boyunca uygulanacak ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar; bu faktör sayfa uzayı birimlerinden .01mm birimlerine dönüştürür. |
| [getEyScale()](#getEyScale--) | Y ekseni boyunca uygulanacak ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar; bu faktör sayfa uzayı birimlerinden .01mm birimlerine dönüştürür. |
| [setEyScale(float value)](#setEyScale-float-) | Y ekseni boyunca uygulanacak ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar; bu faktör sayfa uzayı birimlerinden .01mm birimlerine dönüştürür. |
| [getAEmrText()](#getAEmrText--) | 8 bit ASCII karakterleri, metin öznitelikleri ve boşluk değerleriyle çıkış dizesini belirten bir EmrText nesnesini (bölüm 2.2.5) alır veya ayarlar. |
| [setAEmrText(EmfText value)](#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-) | 8 bit ASCII karakterleri, metin öznitelikleri ve boşluk değerleriyle çıkış dizesini belirten bir EmrText nesnesini (bölüm 2.2.5) alır veya ayarlar. |
### EmfExtTextOutA(EmfRecord source) {#EmfExtTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtTextOutA(EmfRecord source)
```


Yeni bir `EmfExtTextOutA` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfExtTextOutA() {#EmfExtTextOutA--}
```
public EmfExtTextOutA()
```


Yeni bir [EmfExtTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta) sınıfı örneği başlatır.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). Kullanılmaz ve alındığında YOK SAYILMELİDİR.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). Kullanılmaz ve alındığında YOK SAYILMELİDİR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


GraphicsMode numaralandırmasından (bölüm 2.1.16) grafik modunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar.

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


GraphicsMode numaralandırmasından (bölüm 2.1.16) grafik modunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


X ekseni boyunca uygulanacak ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar; bu faktör sayfa uzayı birimlerinden .01mm birimlerine dönüştürür. Bu, iGraphicsMode tarafından belirtilen grafik modu GM\_COMPATIBLE olduğunda yalnızca kullanılmalıdır.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


X ekseni boyunca uygulanacak ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar; bu faktör sayfa uzayı birimlerinden .01mm birimlerine dönüştürür. Bu, iGraphicsMode tarafından belirtilen grafik modu GM\_COMPATIBLE olduğunda yalnızca kullanılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Y ekseni boyunca uygulanacak ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar; bu faktör sayfa uzayı birimlerinden .01mm birimlerine dönüştürür. Bu, iGraphicsMode tarafından belirtilen grafik modu GM\_COMPATIBLE olduğunda yalnızca kullanılmalıdır.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Y ekseni boyunca uygulanacak ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar; bu faktör sayfa uzayı birimlerinden .01mm birimlerine dönüştürür. Bu, iGraphicsMode tarafından belirtilen grafik modu GM\_COMPATIBLE olduğunda yalnızca kullanılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getAEmrText() {#getAEmrText--}
```
public EmfText getAEmrText()
```


8 bit ASCII karakterleri, metin öznitelikleri ve boşluk değerleriyle çıkış dizesini belirten bir EmrText nesnesini (bölüm 2.2.5) alır veya ayarlar.

**Returns:**
[EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext)
### setAEmrText(EmfText value) {#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-}
```
public void setAEmrText(EmfText value)
```


8 bit ASCII karakterleri, metin öznitelikleri ve boşluk değerleriyle çıkış dizesini belirten bir EmrText nesnesini (bölüm 2.2.5) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

