---
title: "EmfMaskBlt"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_MASKBLT kaydı, belirtilen ön plan ve arka plan raster işlemlerine göre bir renk maskesi bitmapi uygulanarak, isteğe bağlı olarak bir fırça deseniyle birleştirilen, kaynak bitmapten hedef dikdörtgene piksel blok transferini tanımlar."
type: docs
weight: 69
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfMaskBlt extends EmfBitmapRecordType
```

EMR\_MASKBLT kaydı, bir kaynak bitmap'ten bir hedef dikdörtgene piksel blok aktarımını, isteğe bağlı olarak bir fırça deseniyle ve bir renk maskesi bitmap uygulamasıyla, belirtilen ön plan ve arka plan raster işlemlerine göre belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfMaskBlt(EmfRecord source)](#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfMaskBlt` sınıfının yeni bir örneğini başlatır. |
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
| [getRop4()](#getRop4--) | Bir bitmapin ön plan ve arka plan renkleri için üçlü raster işlemlerini belirten dörtlü raster işlemini alır veya ayarlar. |
| [setRop4(EmfRop4 value)](#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-) | Bir bitmapin ön plan ve arka plan renkleri için üçlü raster işlemlerini belirten dörtlü raster işlemini alır veya ayarlar. |
| [getXSrc()](#getXSrc--) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setXSrc(int value)](#setXSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getYSrc()](#getYSrc--) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setYSrc(int value)](#setYSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getXformSrc()](#getXformSrc--) | Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28). |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28). |
| [getArgb32BkColorSrc()](#getArgb32BkColorSrc--) | Alır veya ayarlar, kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi ([MS-WMF] bölüm 2.2.2.8). |
| [setArgb32BkColorSrc(int value)](#setArgb32BkColorSrc-int-) | Alır veya ayarlar, kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi ([MS-WMF] bölüm 2.2.2.8). |
| [getUsageSrc()](#getUsageSrc--) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [getXMask()](#getXMask--) | Maske bitmapinin sol üst köşesinin mantıksal x koordinatını belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar. |
| [setXMask(int value)](#setXMask-int-) | Maske bitmapinin sol üst köşesinin mantıksal x koordinatını belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar. |
| [getYMask()](#getYMask--) | Maske bitmapinin sol üst köşesinin mantıksal y koordinatını belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar. |
| [setYMask(int value)](#setYMask-int-) | Maske bitmapinin sol üst köşesinin mantıksal y koordinatını belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar. |
| [getUsageMask()](#getUsageMask--) | Maske bitmap başlığındaki renk tablosu değerlerinin nasıl yorumlanacağını belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. |
| [setUsageMask(int value)](#setUsageMask-int-) | Maske bitmap başlığındaki renk tablosu değerlerinin nasıl yorumlanacağını belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. |
| [getSourceBitmap()](#getSourceBitmap--) | EMR\_MASKBLT kaydının sabit kısmı veya birbirleriyle bitişik olmaları gerekmeyen kaynak bitmapleri içeren bir tamponu alır veya ayarlar. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | EMR\_MASKBLT kaydının sabit kısmı veya birbirleriyle bitişik olmaları gerekmeyen kaynak bitmapleri içeren bir tamponu alır veya ayarlar. |
| [getMaskBitmap()](#getMaskBitmap--) | EMR\_MASKBLT kaydının sabit kısmı veya birbirleriyle bitişik olmaları gerekmeyen maske bitmaplerini içeren bir tamponu alır veya ayarlar. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | EMR\_MASKBLT kaydının sabit kısmı veya birbirleriyle bitişik olmaları gerekmeyen maske bitmaplerini içeren bir tamponu alır veya ayarlar. |
### EmfMaskBlt(EmfRecord source) {#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMaskBlt(EmfRecord source)
```


`EmfMaskBlt` sınıfının yeni bir örneğini başlatır.

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

### getRop4() {#getRop4--}
```
public EmfRop4 getRop4()
```


Bir bitmapin ön plan ve arka plan renkleri için üçlü raster işlemlerini belirten dörtlü raster işlemini alır veya ayarlar. Bu değerler, kaynak dikdörtgenin renk verisinin hedef dikdörtgenin renk verisiyle nasıl birleştirileceğini tanımlar.

**Returns:**
[EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4)
### setRop4(EmfRop4 value) {#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-}
```
public void setRop4(EmfRop4 value)
```


Bir bitmapin ön plan ve arka plan renkleri için üçlü raster işlemlerini belirten dörtlü raster işlemini alır veya ayarlar. Bu değerler, kaynak dikdörtgenin renk verisinin hedef dikdörtgenin renk verisiyle nasıl birleştirileceğini tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4) |  |

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

### getArgb32BkColorSrc() {#getArgb32BkColorSrc--}
```
public int getArgb32BkColorSrc()
```


Alır veya ayarlar, kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi ([MS-WMF] bölüm 2.2.2.8).

**Returns:**
int
### setArgb32BkColorSrc(int value) {#setArgb32BkColorSrc-int-}
```
public void setArgb32BkColorSrc(int value)
```


Alır veya ayarlar, kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi ([MS-WMF] bölüm 2.2.2.8).

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

### getXMask() {#getXMask--}
```
public int getXMask()
```


Maske bitmapinin sol üst köşesinin mantıksal x koordinatını belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar.

**Returns:**
int
### setXMask(int value) {#setXMask-int-}
```
public void setXMask(int value)
```


Maske bitmapinin sol üst köşesinin mantıksal x koordinatını belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getYMask() {#getYMask--}
```
public int getYMask()
```


Maske bitmapinin sol üst köşesinin mantıksal y koordinatını belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar.

**Returns:**
int
### setYMask(int value) {#setYMask-int-}
```
public void setYMask(int value)
```


Maske bitmapinin sol üst köşesinin mantıksal y koordinatını belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getUsageMask() {#getUsageMask--}
```
public int getUsageMask()
```


Maske bitmap başlığındaki renk tablosu değerlerinin nasıl yorumlanacağını belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. Bu değer DIBColors enumerasyonunda olmalıdır.

**Returns:**
int
### setUsageMask(int value) {#setUsageMask-int-}
```
public void setUsageMask(int value)
```


Maske bitmap başlığındaki renk tablosu değerlerinin nasıl yorumlanacağını belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. Bu değer DIBColors enumerasyonunda olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


EMR\_MASKBLT kaydının sabit kısmı veya birbirleriyle bitişik olmaları gerekmeyen kaynak bitmapleri içeren bir tamponu alır veya ayarlar. Bu nedenle, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve YOK SAYILMALIDIR.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


EMR\_MASKBLT kaydının sabit kısmı veya birbirleriyle bitişik olmaları gerekmeyen kaynak bitmapleri içeren bir tamponu alır veya ayarlar. Bu nedenle, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve YOK SAYILMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


EMR\_MASKBLT kaydının sabit kısmı veya birbirleriyle bitişik olmaları gerekmeyen maske bitmapleri içeren bir tamponu alır veya ayarlar. Bu nedenle, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve YOK SAYILMALIDIR.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


EMR\_MASKBLT kaydının sabit kısmı veya birbirleriyle bitişik olmaları gerekmeyen maske bitmapleri içeren bir tamponu alır veya ayarlar. Bu nedenle, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve YOK SAYILMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

