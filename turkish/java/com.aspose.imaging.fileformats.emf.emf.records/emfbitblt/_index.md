---
title: "EmfBitBlt"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_BITBLT kaydı, belirtilen bir raster işlemi doğrultusunda, isteğe bağlı olarak bir fırça deseniyle birleştirilmiş şekilde, kaynak bitmap'ten hedef dikdörtgene bir piksel bloğu aktarımını belirtir."
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfBitBlt extends EmfBitmapRecordType
```

EMR\_BITBLT kaydı, belirtilen bir raster işlemi doğrultusunda, isteğe bağlı olarak bir fırça deseniyle birlikte, bir kaynak bitmap'ten hedef dikdörtgene piksel blok transferini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfBitBlt(EmfRecord source)](#EmfBitBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfBitBlt` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | Alır veya ayarlar, cihaz birimlerinde hedef sınırlama dikdörtgenini tanımlayan bir WMF RectL nesnesi ([MS-WMF] bölüm 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Alır veya ayarlar, cihaz birimlerinde hedef sınırlama dikdörtgenini tanımlayan bir WMF RectL nesnesi ([MS-WMF] bölüm 2.2.2.19). |
| [getXDest()](#getXDest--) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setXDest(int value)](#setXDest-int-) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getYDest()](#getYDest--) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setYDest(int value)](#setYDest-int-) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getCxDest()](#getCxDest--) | Kaynak ve hedef dikdörtgenlerin mantıksal genişliğini belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar. |
| [setCxDest(int value)](#setCxDest-int-) | Kaynak ve hedef dikdörtgenlerin mantıksal genişliğini belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar. |
| [getCyDest()](#getCyDest--) | Kaynak ve hedef dikdörtgenlerin mantıksal yüksekliğini belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar. |
| [setCyDest(int value)](#setCyDest-int-) | Kaynak ve hedef dikdörtgenlerin mantıksal yüksekliğini belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar. |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Raster işlem kodunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Raster işlem kodunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getXSrc()](#getXSrc--) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setXSrc(int value)](#setXSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getYSrc()](#getYSrc--) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setYSrc(int value)](#setYSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getXformSrc()](#getXformSrc--) | Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28). |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28). |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | Alır veya ayarlar, kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi ([MS-WMF] bölüm 2.2.2.8). |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | Alır veya ayarlar, kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi ([MS-WMF] bölüm 2.2.2.8). |
| [getUsageSrc()](#getUsageSrc--) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [getSourceBitmap()](#getSourceBitmap--) | EMR\_BITBLT kaydının sabit kısmıyla bitişik olması gerekmeyen, kaynak bitmap'i içeren bir tamponu alır veya ayarlar. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | EMR\_BITBLT kaydının sabit kısmıyla bitişik olması gerekmeyen, kaynak bitmap'i içeren bir tamponu alır veya ayarlar. |
### EmfBitBlt(EmfRecord source) {#EmfBitBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfBitBlt(EmfRecord source)
```


Yeni bir `EmfBitBlt` sınıfı örneği başlatır.

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


Kaynak ve hedef dikdörtgenlerin mantıksal genişliğini belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Kaynak ve hedef dikdörtgenlerin mantıksal genişliğini belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Kaynak ve hedef dikdörtgenlerin mantıksal yüksekliğini belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Kaynak ve hedef dikdörtgenlerin mantıksal yüksekliğini belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


Raster işlem kodunu belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. Bu kod, kaynak dikdörtgenin renk verisinin hedef dikdörtgenin renk verisiyle ve isteğe bağlı olarak bir fırça deseniyle nasıl birleştirileceğini tanımlar, böylece nihai renk elde edilir.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


Raster işlem kodunu belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. Bu kod, kaynak dikdörtgenin renk verisinin hedef dikdörtgenin renk verisiyle ve isteğe bağlı olarak bir fırça deseniyle nasıl birleştirileceğini tanımlar, böylece nihai renk elde edilir.

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

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


EMR\_BITBLT kaydının sabit kısmıyla bitişik olması gerekmeyen, kaynak bitmap'i içeren bir tamponu alır veya ayarlar. Buna göre, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve MUST yok sayılmalıdır.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


EMR\_BITBLT kaydının sabit kısmıyla bitişik olması gerekmeyen, kaynak bitmap'i içeren bir tamponu alır veya ayarlar. Buna göre, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve MUST yok sayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

