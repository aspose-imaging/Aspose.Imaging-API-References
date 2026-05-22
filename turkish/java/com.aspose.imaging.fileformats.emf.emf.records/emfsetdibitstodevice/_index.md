---
title: "EmfSetDiBitsToDevice"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SETDIBITSTODEVICE kaydı, kaynak bitmap'in belirtilen tarama satırlarından hedef dikdörtgene piksel blok aktarımını belirtir."
type: docs
weight: 124
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfSetDiBitsToDevice extends EmfBitmapRecordType
```

EMR\_SETDIBITSTODEVICE kaydı, bir kaynak bitmap'in belirtilen tarama satırlarından hedef dikdörtgene piksel blok transferini tanımlar.

Bu kayıt, JPEG ve PNG formatındaki kaynak görüntüleri destekler. Kaynak bitmap başlığındaki Sıkıştırma alanı görüntü formatını belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSetDiBitsToDevice(EmfRecord source)](#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfSetDiBitsToDevice` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | Alır veya ayarlar, cihaz birimlerinde hedef sınırlama dikdörtgenini tanımlayan bir WMF RectL nesnesi ([MS-WMF] bölüm 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Alır veya ayarlar, cihaz birimlerinde hedef sınırlama dikdörtgenini tanımlayan bir WMF RectL nesnesi ([MS-WMF] bölüm 2.2.2.19). |
| [getXDest()](#getXDest--) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setXDest(int value)](#setXDest-int-) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getYDest()](#getYDest--) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setYDest(int value)](#setYDest-int-) | Alır veya ayarlar, hedef dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getXSrc()](#getXSrc--) | Kaynak dikdörtgenin sol-alt köşesinin piksel cinsinden x koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setXSrc(int value)](#setXSrc-int-) | Kaynak dikdörtgenin sol-alt köşesinin piksel cinsinden x koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getYSrc()](#getYSrc--) | Kaynak dikdörtgenin sol-alt köşesinin piksel cinsinden y koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setYSrc(int value)](#setYSrc-int-) | Kaynak dikdörtgenin sol-alt köşesinin piksel cinsinden y koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getCxSrc()](#getCxSrc--) | Kaynak dikdörtgenin piksel cinsinden genişliğini belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar. |
| [setCxSrc(int value)](#setCxSrc-int-) | Kaynak dikdörtgenin piksel cinsinden genişliğini belirten 32-bit işaretli bir tamsayıyı alır veya ayarlar. |
| [getCySrc()](#getCySrc--) | Kaynak dikdörtgenin piksel cinsinden yüksekliğini belirten 32 bit işaretli tam sayıyı alır veya ayarlar |
| [setCySrc(int value)](#setCySrc-int-) | Kaynak dikdörtgenin piksel cinsinden yüksekliğini belirten 32 bit işaretli tam sayıyı alır veya ayarlar |
| [getUsageSrc()](#getUsageSrc--) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [getIStartScan()](#getIStartScan--) | Dizideki ilk tarama satırını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setIStartScan(int value)](#setIStartScan-int-) | Dizideki ilk tarama satırını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getCScans()](#getCScans--) | Tarama satırlarının sayısını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setCScans(int value)](#setCScans-int-) | Tarama satırlarının sayısını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getSourceBitmap()](#getSourceBitmap--) | EMR\_SETDIBITSTODEVICE kaydının sabit kısmıyla bitişik olması gerekmeyen kaynak bitmap'i içeren bir tamponu alır veya ayarlar. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | EMR\_SETDIBITSTODEVICE kaydının sabit kısmıyla bitişik olması gerekmeyen kaynak bitmap'i içeren bir tamponu alır veya ayarlar. |
### EmfSetDiBitsToDevice(EmfRecord source) {#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetDiBitsToDevice(EmfRecord source)
```


Yeni bir `EmfSetDiBitsToDevice` sınıfı örneği başlatır.

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


Kaynak dikdörtgenin sol-alt köşesinin piksel cinsinden x koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Kaynak dikdörtgenin sol-alt köşesinin piksel cinsinden x koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Kaynak dikdörtgenin sol-alt köşesinin piksel cinsinden y koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Kaynak dikdörtgenin sol-alt köşesinin piksel cinsinden y koordinatını belirten 32 bit işaretli tam sayıyı alır veya ayarlar.

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


Kaynak dikdörtgenin piksel cinsinden yüksekliğini belirten 32 bit işaretli tam sayıyı alır veya ayarlar

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Kaynak dikdörtgenin piksel cinsinden yüksekliğini belirten 32 bit işaretli tam sayıyı alır veya ayarlar

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

### getIStartScan() {#getIStartScan--}
```
public int getIStartScan()
```


Dizideki ilk tarama satırını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setIStartScan(int value) {#setIStartScan-int-}
```
public void setIStartScan(int value)
```


Dizideki ilk tarama satırını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCScans() {#getCScans--}
```
public int getCScans()
```


Tarama satırlarının sayısını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setCScans(int value) {#setCScans-int-}
```
public void setCScans(int value)
```


Tarama satırlarının sayısını belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


EMR\_SETDIBITSTODEVICE kaydının sabit kısmıyla bitişik olması gerekmeyen kaynak bitmap'i içeren bir tamponu alır veya ayarlar. Buna göre, bu tampon içinde "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve YOK SAYILMALIDIR.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


EMR\_SETDIBITSTODEVICE kaydının sabit kısmıyla bitişik olması gerekmeyen kaynak bitmap'i içeren bir tamponu alır veya ayarlar. Buna göre, bu tampon içinde "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve YOK SAYILMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

