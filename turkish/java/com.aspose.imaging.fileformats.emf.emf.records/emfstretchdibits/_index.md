---
title: "EmfStretchDiBits"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_STRETCHDIBITS kaydı, gerektiğinde çıktıyı hedefin boyutlarına sığdırmak için uzatarak veya sıkıştırarak, belirtilen raster işlemi doğrultusunda, bir fırça deseniyle birlikte isteğe bağlı olarak, kaynak bitmap'ten hedef dikdörtgene piksel blok transferini belirtir."
type: docs
weight: 150
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchDiBits extends EmfBitmapRecordType
```

EMR\_STRETCHDIBITS kaydı, bir kaynak bitmap'ten bir hedef dikdörtgene piksel bloğu aktarımını, isteğe bağlı olarak bir fırça deseniyle birlikte, belirtilen bir raster işlemi doğrultusunda, çıktıyı hedefin boyutlarına sığdırmak için gerekirse gererek veya sıkıştırarak belirtir.

Bu kayıt, JPEG ve PNG formatındaki kaynak görüntüleri destekler. Kaynak bitmap başlığındaki Compression alanı görüntü formatını belirtir. Kaynak ve hedef yüksekliği ve genişliği alanlarının işaretleri farklıysa, bu kayıt kaynak bitmap'in hedefe ayna görüntüsü kopyasını belirtir. Yani, cxSrc ve cxDest farklı işaretlere sahipse, kaynak bitmap'in x ekseni boyunca ayna görüntüsü belirtilir. cySrc ve cyDest farklı işaretlere sahipse, kaynak bitmap'in y ekseni boyunca ayna görüntüsü belirtilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfStretchDiBits(EmfRecord source)](#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfStretchDiBits` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | Alır veya ayarlar, cihaz birimlerinde hedef sınırlama dikdörtgenini tanımlayan bir WMF RectL nesnesi ([MS-WMF] bölüm 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Alır veya ayarlar, cihaz birimlerinde hedef sınırlama dikdörtgenini tanımlayan bir WMF RectL nesnesi ([MS-WMF] bölüm 2.2.2.19). |
| [getXDest()](#getXDest--) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setXDest(int value)](#setXDest-int-) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getYDest()](#getYDest--) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setYDest(int value)](#setYDest-int-) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getXSrc()](#getXSrc--) | Kaynak dikdörtgenin sol üst köşesinin piksel cinsinden x koordinatını belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar. |
| [setXSrc(int value)](#setXSrc-int-) | Kaynak dikdörtgenin sol üst köşesinin piksel cinsinden x koordinatını belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar. |
| [getYSrc()](#getYSrc--) | Kaynak dikdörtgenin sol üst köşesinin piksel cinsinden y koordinatını belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar. |
| [setYSrc(int value)](#setYSrc-int-) | Kaynak dikdörtgenin sol üst köşesinin piksel cinsinden y koordinatını belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar. |
| [getCxSrc()](#getCxSrc--) | Kaynak dikdörtgenin piksel cinsinden genişliğini belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar. |
| [setCxSrc(int value)](#setCxSrc-int-) | Kaynak dikdörtgenin piksel cinsinden genişliğini belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar. |
| [getCySrc()](#getCySrc--) | Kaynak dikdörtgenin piksel cinsinden yüksekliğini belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar. |
| [setCySrc(int value)](#setCySrc-int-) | Kaynak dikdörtgenin piksel cinsinden yüksekliğini belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar. |
| [getUsageSrc()](#getUsageSrc--) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Bir raster işlem kodunu belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Bir raster işlem kodunu belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [getCxDest()](#getCxDest--) | Alır veya ayarlar, hedef dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. |
| [setCxDest(int value)](#setCxDest-int-) | Alır veya ayarlar, hedef dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. |
| [getCyDest()](#getCyDest--) | Alır veya ayarlar, hedef dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. |
| [setCyDest(int value)](#setCyDest-int-) | Alır veya ayarlar, hedef dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. |
| [getSourceBitmap()](#getSourceBitmap--) | EMR\_STRETCHDIBITS kaydının sabit kısmıyla bitişik olmasına gerek olmayan, kaynak bitmap'i içeren bir tamponu alır veya ayarlar. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | EMR\_STRETCHDIBITS kaydının sabit kısmıyla bitişik olmasına gerek olmayan, kaynak bitmap'i içeren bir tamponu alır veya ayarlar. |
### EmfStretchDiBits(EmfRecord source) {#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchDiBits(EmfRecord source)
```


`EmfStretchDiBits` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Alır veya ayarlar, cihaz birimlerinde hedef sınırlama dikdörtgenini tanımlayan bir WMF RectL nesnesi ([MS-WMF] bölüm 2.2.2.19).

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Alır veya ayarlar, cihaz birimlerinde hedef sınırlama dikdörtgenini tanımlayan bir WMF RectL nesnesi ([MS-WMF] bölüm 2.2.2.19).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Kaynak dikdörtgenin sol üst köşesinin piksel cinsinden x koordinatını belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Kaynak dikdörtgenin sol üst köşesinin piksel cinsinden x koordinatını belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Kaynak dikdörtgenin sol üst köşesinin piksel cinsinden y koordinatını belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Kaynak dikdörtgenin sol üst köşesinin piksel cinsinden y koordinatını belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Kaynak dikdörtgenin piksel cinsinden genişliğini belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Kaynak dikdörtgenin piksel cinsinden genişliğini belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Kaynak dikdörtgenin piksel cinsinden yüksekliğini belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Kaynak dikdörtgenin piksel cinsinden yüksekliğini belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. Bu değer DIBColors numaralandırmasında (bölüm 2.1.9) yer almalıdır.

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. Bu değer DIBColors numaralandırmasında (bölüm 2.1.9) yer almalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


Bir raster işlem kodunu belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. Bu kodlar, kaynak dikdörtgenin renk verisinin hedef dikdörtgenin renk verisiyle ve isteğe bağlı olarak bir fırça deseniyle nasıl birleştirileceğini tanımlayarak nihai rengi elde eder.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


Bir raster işlem kodunu belirten 32-bit işaretsiz bir tamsayıyı alır veya ayarlar. Bu kodlar, kaynak dikdörtgenin renk verisinin hedef dikdörtgenin renk verisiyle ve isteğe bağlı olarak bir fırça deseniyle nasıl birleştirileceğini tanımlayarak nihai rengi elde eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


Alır veya ayarlar, hedef dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Alır veya ayarlar, hedef dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Alır veya ayarlar, hedef dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Alır veya ayarlar, hedef dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


EMR\_STRETCHDIBITS kaydının sabit kısmıyla bitişik olmasına gerek olmayan, kaynak bitmap'i içeren bir tamponu alır veya ayarlar. Bu nedenle, bu tampondaki \"UndefinedSpace\" olarak etiketlenmiş alanlar isteğe bağlıdır ve YOK SAYILMALIDIR.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


EMR\_STRETCHDIBITS kaydının sabit kısmıyla bitişik olmasına gerek olmayan, kaynak bitmap'i içeren bir tamponu alır veya ayarlar. Bu nedenle, bu tampondaki \"UndefinedSpace\" olarak etiketlenmiş alanlar isteğe bağlıdır ve YOK SAYILMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

