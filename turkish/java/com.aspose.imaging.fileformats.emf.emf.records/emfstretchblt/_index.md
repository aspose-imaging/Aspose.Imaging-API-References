---
title: "EmfStretchBlt"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_STRETCHBLT kaydı, bir kaynak bitmap'ten bir hedef dikdörtgene, isteğe bağlı olarak bir fırça deseniyle birlikte, belirtilen bir raster işlemi kullanarak piksel blok transferini tanımlar; gerekirse çıktıyı hedefin boyutlarına sığdırmak için gererek veya sıkıştırarak."
type: docs
weight: 149
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchBlt extends EmfBitmapRecordType
```

EMR\_STRETCHBLT kaydı, bir kaynak bitmap'ten bir hedef dikdörtgene piksel bloğu aktarımını, isteğe bağlı olarak bir fırça deseniyle birlikte, belirtilen bir raster işlemi doğrultusunda, çıktıyı hedefin boyutlarına sığdırmak için gerekirse gererek veya sıkıştırarak belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfStretchBlt(EmfRecord source)](#EmfStretchBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfStretchBlt` sınıfının yeni bir örneğini başlatır. |
| [EmfStretchBlt()](#EmfStretchBlt--) | `EmfStretchBlt` sınıfının yeni bir örneğini başlatır. |
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
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Raster işlem kodunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Raster işlem kodunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
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
| [getCxSrc()](#getCxSrc--) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. |
| [setCxSrc(int value)](#setCxSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. |
| [getCySrc()](#getCySrc--) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. |
| [setCySrc(int value)](#setCySrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. |
| [getSourceBitmap()](#getSourceBitmap--) | EMR\\_STRETCHBLT kaydının sabit kısmı ile bitişik olması gerekmeyen kaynak bitmap'i içeren bir tamponu alır veya ayarlar. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | EMR\\_STRETCHBLT kaydının sabit kısmı ile bitişik olması gerekmeyen kaynak bitmap'i içeren bir tamponu alır veya ayarlar. |
| [getSrcRect()](#getSrcRect--) | Kaynak dikdörtgeni alır veya ayarlar. |
| [setSrcRect(Rectangle value)](#setSrcRect-com.aspose.imaging.Rectangle-) | Kaynak dikdörtgeni alır veya ayarlar. |
| [getDestRect()](#getDestRect--) | Hedef dikdörtgeni alır veya ayarlar. |
| [setDestRect(Rectangle value)](#setDestRect-com.aspose.imaging.Rectangle-) | Hedef dikdörtgeni alır veya ayarlar. |
### EmfStretchBlt(EmfRecord source) {#EmfStretchBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchBlt(EmfRecord source)
```


`EmfStretchBlt` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfStretchBlt() {#EmfStretchBlt--}
```
public EmfStretchBlt()
```


`EmfStretchBlt` sınıfının yeni bir örneğini başlatır.

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

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


32 bit işaretsiz tamsayıyı alır veya ayarlar; bu tamsayı raster işlem kodunu belirtir. Bu kod, kaynak dikdörtgenin renk verisinin hedef dikdörtgenin renk verisiyle ve isteğe bağlı olarak bir fırça deseniyle nasıl birleştirileceğini tanımlar, böylece son renk elde edilir.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


32 bit işaretsiz tamsayıyı alır veya ayarlar; bu tamsayı raster işlem kodunu belirtir. Bu kod, kaynak dikdörtgenin renk verisinin hedef dikdörtgenin renk verisiyle ve isteğe bağlı olarak bir fırça deseniyle nasıl birleştirileceğini tanımlar, böylece son renk elde edilir.

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


Kaynak bitmap'i içeren bir tamponu alır veya ayarlar; bu tamponun EMR\_STRETCHBLT kaydının sabit kısmıyla bitişik olması gerekmez. Bu nedenle, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve YOK SAYILMALIdır.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Kaynak bitmap'i içeren bir tamponu alır veya ayarlar; bu tamponun EMR\_STRETCHBLT kaydının sabit kısmıyla bitişik olması gerekmez. Bu nedenle, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve YOK SAYILMALIdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getSrcRect() {#getSrcRect--}
```
public Rectangle getSrcRect()
```


Kaynak dikdörtgeni alır veya ayarlar.

Değer: Kaynak dikdörtgen.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setSrcRect(Rectangle value) {#setSrcRect-com.aspose.imaging.Rectangle-}
```
public void setSrcRect(Rectangle value)
```


Kaynak dikdörtgeni alır veya ayarlar.

Değer: Kaynak dikdörtgen.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getDestRect() {#getDestRect--}
```
public Rectangle getDestRect()
```


Hedef dikdörtgeni alır veya ayarlar.

Değer: Hedef dikdörtgen.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setDestRect(Rectangle value) {#setDestRect-com.aspose.imaging.Rectangle-}
```
public void setDestRect(Rectangle value)
```


Hedef dikdörtgeni alır veya ayarlar.

Değer: Hedef dikdörtgen.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

