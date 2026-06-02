---
title: "EmfSmallTextOut"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SMALLTEXTOUT kaydı bir dize çıktısı verir."
type: docs
weight: 147
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSmallTextOut extends EmfDrawingRecordType
```

EMR\_SMALLTEXTOUT kaydı, bir dize çıktılar.

fuOptions alanında ETO\_SMALL\_CHARS ayarlanmışsa, TextString 8 bitlik karakter kodlarını içerir; bu kodlar, yüksek baytın 0 varsayıldığı 16 bitlik Unicode UTF16-LE karakter kodlarının düşük baytlarından türetilir. fuOptions alanında ETO\_NO\_RECT ayarlanmışsa, Bounds alanı kayıtta yer almaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSmallTextOut(EmfRecord source)](#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfSmallTextOut` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getX()](#getX--) | Dizeyi yerleştirilecek x koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setX(int value)](#setX-int-) | Dizeyi yerleştirilecek x koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getY()](#getY--) | Dizeyi yerleştirilecek y koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setY(int value)](#setY-int-) | Dizeyi yerleştirilecek y koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getCChars()](#getCChars--) | Dizedeki 16 bitlik karakter sayısını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setCChars(int value)](#setCChars-int-) | Dizedeki 16 bitlik karakter sayısını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getFuOptions()](#getFuOptions--) | Kullanılacak metin çıkış seçeneklerini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setFuOptions(int value)](#setFuOptions-int-) | Kullanılacak metin çıkış seçeneklerini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getIGraphicsMode()](#getIGraphicsMode--) | GraphicsMode sayımından (bölüm 2.1.16) grafik modunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | GraphicsMode sayımından (bölüm 2.1.16) grafik modunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getExScale()](#getExScale--) | Metni x yönünde ne kadar ölçekleyeceğini belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [setExScale(float value)](#setExScale-float-) | Metni x yönünde ne kadar ölçekleyeceğini belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [getEyScale()](#getEyScale--) | Metni y yönünde ne kadar ölçekleyeceğini belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [setEyScale(float value)](#setEyScale-float-) | Metni y yönünde ne kadar ölçekleyeceğini belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [getBounds()](#getBounds--) | Cihaz birimlerinde sınırlayıcı dikdörtgeni belirten isteğe bağlı, 128 bitlik WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Cihaz birimlerinde sınırlayıcı dikdörtgeni belirten isteğe bağlı, 128 bitlik WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. |
| [getTextString()](#getTextString--) | Çizilecek metin dizesini içeren, fuOptions alanının değerine göre 8 bit veya 16 bit karakter kodlarıyla değişken uzunlukta bir dizeyi alır veya ayarlar. |
| [setTextString(String value)](#setTextString-java.lang.String-) | Çizilecek metin dizesini içeren, fuOptions alanının değerine göre 8 bit veya 16 bit karakter kodlarıyla değişken uzunlukta bir dizeyi alır veya ayarlar. |
### EmfSmallTextOut(EmfRecord source) {#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSmallTextOut(EmfRecord source)
```


Yeni bir `EmfSmallTextOut` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getX() {#getX--}
```
public int getX()
```


Dizeyi yerleştirilecek x koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Dizeyi yerleştirilecek x koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getY() {#getY--}
```
public int getY()
```


Dizeyi yerleştirilecek y koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Dizeyi yerleştirilecek y koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCChars() {#getCChars--}
```
public int getCChars()
```


Dizedeki 16 bitlik karakter sayısını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Dize NULL ile sonlandırılmaz.

**Returns:**
int
### setCChars(int value) {#setCChars-int-}
```
public void setCChars(int value)
```


Dizedeki 16 bitlik karakter sayısını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Dize NULL ile sonlandırılmaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFuOptions() {#getFuOptions--}
```
public int getFuOptions()
```


Kullanılacak metin çıkış seçeneklerini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu seçenekler, ExtTextOutOptions sayımından (bölüm 2.1.11) bir veya birden fazla değerle belirtilir.

**Returns:**
int
### setFuOptions(int value) {#setFuOptions-int-}
```
public void setFuOptions(int value)
```


Kullanılacak metin çıkış seçeneklerini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu seçenekler, ExtTextOutOptions sayımından (bölüm 2.1.11) bir veya birden fazla değerle belirtilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


GraphicsMode sayımından (bölüm 2.1.16) grafik modunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


GraphicsMode sayımından (bölüm 2.1.16) grafik modunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Metni x yönünde ne kadar ölçekleyeceğini belirten 32 bit kayan nokta değerini alır veya ayarlar.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Metni x yönünde ne kadar ölçekleyeceğini belirten 32 bit kayan nokta değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Metni y yönünde ne kadar ölçekleyeceğini belirten 32 bit kayan nokta değerini alır veya ayarlar.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Metni y yönünde ne kadar ölçekleyeceğini belirten 32 bit kayan nokta değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Cihaz birimlerinde sınırlayıcı dikdörtgeni belirten isteğe bağlı, 128 bitlik WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Cihaz birimlerinde sınırlayıcı dikdörtgeni belirten isteğe bağlı, 128 bitlik WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getTextString() {#getTextString--}
```
public String getTextString()
```


Çizilecek metin dizesini içeren, fuOptions alanının değerine göre 8 bit veya 16 bit karakter kodlarıyla değişken uzunlukta bir dizeyi alır veya ayarlar.

**Returns:**
java.lang.String
### setTextString(String value) {#setTextString-java.lang.String-}
```
public void setTextString(String value)
```


Çizilecek metin dizesini içeren, fuOptions alanının değerine göre 8 bit veya 16 bit karakter kodlarıyla değişken uzunlukta bir dizeyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

