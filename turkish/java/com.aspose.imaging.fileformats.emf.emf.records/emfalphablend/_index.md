---
title: "EmfAlphaBlend"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_ALPHABLEND kaydı, belirtilen bir karıştırma işlemiyle alfa saydamlık verilerini içeren, kaynak bitmap'ten hedef dikdörtgene piksel blok aktarımını tanımlar."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfAlphaBlend extends EmfBitmapRecordType
```

EMR\_ALPHABLEND kaydı, belirtilen bir karıştırma işlemi doğrultusunda, alfa şeffaflık verileri dahil olmak üzere, bir kaynak bitmap'ten hedef dikdörtgene piksel blok transferini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfAlphaBlend(EmfRecord source)](#EmfAlphaBlend-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfAlphaBlend` sınıfı örneği başlatır. |
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
| [getBlendFunction()](#getBlendFunction--) | Alır veya ayarlar, kaynak ve hedef bitmap'ler için karıştırma işlemlerini belirten bir yapı. |
| [setBlendFunction(EmfBlendFunction value)](#setBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) | Alır veya ayarlar, kaynak ve hedef bitmap'ler için karıştırma işlemlerini belirten bir yapı. |
| [getXSrc()](#getXSrc--) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setXSrc(int value)](#setXSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getYSrc()](#getYSrc--) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setYSrc(int value)](#setYSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getXformSr()](#getXformSr--) | Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28). |
| [setXformSr(Matrix value)](#setXformSr-com.aspose.imaging.Matrix-) | Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28). |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | Alır veya ayarlar, kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi ([MS-WMF] bölüm 2.2.2.8). |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | Alır veya ayarlar, kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi ([MS-WMF] bölüm 2.2.2.8). |
| [getUsageSrc()](#getUsageSrc--) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [getCxSrc()](#getCxSrc--) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. |
| [setCxSrc(int value)](#setCxSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. |
| [getCySrc()](#getCySrc--) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. |
| [setCySrc(int value)](#setCySrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. |
| [getSourceBitmap()](#getSourceBitmap--) | Alır veya ayarlar, EMR\_ALPHABLEND kaydının sabit kısmı ile bitişik olması gerekmeyen kaynak bitmap'i içeren bir tampon. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Alır veya ayarlar, EMR\_ALPHABLEND kaydının sabit kısmı ile bitişik olması gerekmeyen kaynak bitmap'i içeren bir tampon. |
### EmfAlphaBlend(EmfRecord source) {#EmfAlphaBlend-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAlphaBlend(EmfRecord source)
```


Yeni bir `EmfAlphaBlend` sınıfı örneği başlatır.

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


Alır veya ayarlar, hedef dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. Bu değer SIFIR'dan büyük olmalıdır.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Alır veya ayarlar, hedef dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. Bu değer SIFIR'dan büyük olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Alır veya ayarlar, hedef dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. Bu değer SIFIR'dan büyük olmalıdır.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Alır veya ayarlar, hedef dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. Bu değer SIFIR'dan büyük olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBlendFunction() {#getBlendFunction--}
```
public EmfBlendFunction getBlendFunction()
```


Alır veya ayarlar, kaynak ve hedef bitmap'ler için karıştırma işlemlerini belirten bir yapı.

**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
### setBlendFunction(EmfBlendFunction value) {#setBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void setBlendFunction(EmfBlendFunction value)
```


Alır veya ayarlar, kaynak ve hedef bitmap'ler için karıştırma işlemlerini belirten bir yapı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

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

### getXformSr() {#getXformSr--}
```
public Matrix getXformSr()
```


Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28).

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSr(Matrix value) {#setXformSr-com.aspose.imaging.Matrix-}
```
public void setXformSr(Matrix value)
```


Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBkSrcArgb32Color() {#getBkSrcArgb32Color--}
```
public int getBkSrcArgb32Color()
```


Alır veya ayarlar, kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi ([MS-WMF] bölüm 2.2.2.8).

Değer: 32 bit ARGB renk

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


Alır veya ayarlar, kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi ([MS-WMF] bölüm 2.2.2.8).

Değer: 32 bit ARGB renk

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

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Alır veya ayarlar, kaynak dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. Bu değer SIFIR'dan büyük olmalıdır.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Alır veya ayarlar, kaynak dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. Bu değer SIFIR'dan büyük olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Alır veya ayarlar, kaynak dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. Bu değer SIFIR'dan büyük olmalıdır.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Alır veya ayarlar, kaynak dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. Bu değer SIFIR'dan büyük olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Alır veya ayarlar, EMR\_ALPHABLEND kaydının sabit kısmı ile bitişik olması gerekmeyen kaynak bitmap'i içeren bir tampon. Bu tampon içinde \"UndefinedSpace\" olarak etiketlenen alanlar isteğe bağlıdır ve YOK SAYILMALIDIR.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Alır veya ayarlar, EMR\_ALPHABLEND kaydının sabit kısmı ile bitişik olması gerekmeyen kaynak bitmap'i içeren bir tampon. Bu tampon içinde \"UndefinedSpace\" olarak etiketlenen alanlar isteğe bağlıdır ve YOK SAYILMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

