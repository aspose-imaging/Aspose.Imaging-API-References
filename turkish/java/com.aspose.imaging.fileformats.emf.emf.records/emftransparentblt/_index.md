---
title: "EmfTransparentBlt"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_TRANSPARENTBLT kaydı, bir kaynak bitmap'ten hedef dikdörtgene piksel blok aktarımını tanımlar; belirtilen rengi şeffaf olarak ele alır, gerekirse çıktıyı hedefin boyutlarına sığdırmak için gerer veya sıkıştırır."
type: docs
weight: 154
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfTransparentBlt extends EmfBitmapRecordType
```

EMR\_TRANSPARENTBLT kaydı, bir kaynak bitmap'ten bir hedef dikdörtgene piksel bloğu aktarımını, belirtilen bir rengi şeffaf olarak işleyerek, çıktıyı hedefin boyutlarına sığdırmak için gerekirse gererek veya sıkıştırarak belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfTransparentBlt(EmfRecord source)](#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfTransparentBlt` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | Alır veya ayarlar, cihaz birimlerinde hedef sınırlama dikdörtgenini tanımlayan bir WMF RectL nesnesi ([MS-WMF] bölüm 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Alır veya ayarlar, cihaz birimlerinde hedef sınırlama dikdörtgenini tanımlayan bir WMF RectL nesnesi ([MS-WMF] bölüm 2.2.2.19). |
| [getXDest()](#getXDest--) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setXDest(int value)](#setXDest-int-) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getYDest()](#getYDest--) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setYDest(int value)](#setYDest-int-) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getCxDest()](#getCxDest--) | Alır veya ayarlar, hedef dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. |
| [setCxDest(int value)](#setCxDest-int-) | Alır veya ayarlar, hedef dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. |
| [getCyDest()](#getCyDest--) | Alır veya ayarlar, hedef dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. |
| [setCyDest(int value)](#setCyDest-int-) | Alır veya ayarlar, hedef dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. |
| [getTransparentArgb32Color()](#getTransparentArgb32Color--) | Kaynak bitmap'te şeffaf olarak işlenecek rengi belirten bir WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar. |
| [setTransparentArgb32Color(int value)](#setTransparentArgb32Color-int-) | Kaynak bitmap'te şeffaf olarak işlenecek rengi belirten bir WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar. |
| [getXSrc()](#getXSrc--) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setXSrc(int value)](#setXSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getYSrc()](#getYSrc--) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setYSrc(int value)](#setYSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getXformSrc()](#getXformSrc--) | Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28). |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28). |
| [getSrcBkArgb32Color()](#getSrcBkArgb32Color--) | Kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesini alır veya ayarlar. |
| [setSrcBkArgb32Color(int value)](#setSrcBkArgb32Color-int-) | Kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesini alır veya ayarlar. |
| [getUsageSrc()](#getUsageSrc--) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [getCxSrc()](#getCxSrc--) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. |
| [setCxSrc(int value)](#setCxSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. |
| [getCySrc()](#getCySrc--) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. |
| [setCySrc(int value)](#setCySrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. |
| [getSourceBitmap()](#getSourceBitmap--) | Kaynak bitmap'i içeren bir tamponu alır veya ayarlar; bu tamponun EMR\_TRANSPARENTBLT kaydının sabit kısmıyla bitişik olması gerekmez. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Kaynak bitmap'i içeren bir tamponu alır veya ayarlar; bu tamponun EMR\_TRANSPARENTBLT kaydının sabit kısmıyla bitişik olması gerekmez. |
### EmfTransparentBlt(EmfRecord source) {#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfTransparentBlt(EmfRecord source)
```


Yeni bir `EmfTransparentBlt` sınıfı örneği başlatır.

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

### getTransparentArgb32Color() {#getTransparentArgb32Color--}
```
public int getTransparentArgb32Color()
```


Kaynak bitmap'te şeffaf olarak işlenecek rengi belirten bir WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar.

**Returns:**
int
### setTransparentArgb32Color(int value) {#setTransparentArgb32Color-int-}
```
public void setTransparentArgb32Color(int value)
```


Kaynak bitmap'te şeffaf olarak işlenecek rengi belirten bir WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getXformSrc() {#getXformSrc--}
```
public Matrix getXformSrc()
```


Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28).

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSrc(Matrix value) {#setXformSrc-com.aspose.imaging.Matrix-}
```
public void setXformSrc(Matrix value)
```


Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getSrcBkArgb32Color() {#getSrcBkArgb32Color--}
```
public int getSrcBkArgb32Color()
```


Kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesini alır veya ayarlar.

**Returns:**
int
### setSrcBkArgb32Color(int value) {#setSrcBkArgb32Color-int-}
```
public void setSrcBkArgb32Color(int value)
```


Kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. Bu değer DIBColors sayımında (bölüm 2.1.9) olmalıdır.

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. Bu değer DIBColors sayımında (bölüm 2.1.9) olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Alır veya ayarlar, kaynak dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Alır veya ayarlar, kaynak dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Alır veya ayarlar, kaynak dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Alır veya ayarlar, kaynak dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Kaynak bitmap'i içeren bir tamponu alır veya ayarlar; bu tamponun EMR\_TRANSPARENTBLT kaydının sabit kısmıyla bitişik olması gerekmez. Bu nedenle, bu tampondaki "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve göz ardı edilmelidir.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Kaynak bitmap'i içeren bir tamponu alır veya ayarlar; bu tamponun EMR\_TRANSPARENTBLT kaydının sabit kısmıyla bitişik olması gerekmez. Bu nedenle, bu tampondaki "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve göz ardı edilmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

