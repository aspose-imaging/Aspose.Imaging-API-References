---
title: "EmfPlgBlt"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_PLGBLT kaydı, bir renk maske bit haritası uygulanarak kaynak bitmap'ten hedef paralelograma piksel blok transferini belirtir."
type: docs
weight: 84
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfPlgBlt extends EmfBitmapRecordType
```

EMR_PLGBLT kaydı, bir renk maske bitmapi uygulanarak kaynak bitmapten hedef paralelograma piksel blok transferini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlgBlt(EmfRecord source)](#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfPlgBlt` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | Hedefe yapılan çıktı için cihaz birimlerinde sınırlayıcı dikdörtgeni tanımlayan WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hedefe yapılan çıktı için cihaz birimlerinde sınırlayıcı dikdörtgeni tanımlayan WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. |
| [getAptlDest()](#getAptlDest--) | Üç WMF PointL nesnesinden oluşan bir dizi alır veya ayarlar ([MS-WMF] bölüm 2.2.2.15) ve bu dizi, blok aktarımı için bir paralelkenar hedef alanının üç köşesini belirtir. |
| [setAptlDest(Point[] value)](#setAptlDest-com.aspose.imaging.Point---) | Üç WMF PointL nesnesinden oluşan bir dizi alır veya ayarlar ([MS-WMF] bölüm 2.2.2.15) ve bu dizi, blok aktarımı için bir paralelkenar hedef alanının üç köşesini belirtir. |
| [getXSrc()](#getXSrc--) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setXSrc(int value)](#setXSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getYSrc()](#getYSrc--) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [setYSrc(int value)](#setYSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı. |
| [getCxSrc()](#getCxSrc--) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. |
| [setCxSrc(int value)](#setCxSrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal genişliğini belirten 32 bit işaretli bir tam sayı. |
| [getCySrc()](#getCySrc--) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. |
| [setCySrc(int value)](#setCySrc-int-) | Alır veya ayarlar, kaynak dikdörtgenin mantıksal yüksekliğini belirten 32 bit işaretli bir tam sayı. |
| [getXFormSrc()](#getXFormSrc--) | Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28). |
| [setXFormSrc(Matrix value)](#setXFormSrc-com.aspose.imaging.Matrix-) | Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28). |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | Kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi alır veya ayarlar ([MS-WMF] bölüm 2.2.2.8). |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | Kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi alır veya ayarlar ([MS-WMF] bölüm 2.2.2.8). |
| [getUsageSrc()](#getUsageSrc--) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Alır veya ayarlar, kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayı. |
| [getXMask()](#getXMask--) | Maske bitmapinin sol üst köşesinin mantıksal x koordinatını belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar. |
| [setXMask(int value)](#setXMask-int-) | Maske bitmapinin sol üst köşesinin mantıksal x koordinatını belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar. |
| [getYMask()](#getYMask--) | Maske bitmapinin sol üst köşesinin mantıksal y koordinatını belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar. |
| [setYMask(int value)](#setYMask-int-) | Maske bitmapinin sol üst köşesinin mantıksal y koordinatını belirten 32 bitlik işaretli tam sayıyı alır veya ayarlar. |
| [getUsageMask()](#getUsageMask--) | Maske bitmap başlığındaki renk tablosu değerlerinin nasıl yorumlanacağını belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. |
| [setUsageMask(int value)](#setUsageMask-int-) | Maske bitmap başlığındaki renk tablosu değerlerinin nasıl yorumlanacağını belirten 32 bitlik işaretsiz tam sayıyı alır veya ayarlar. |
| [getSourceBitmap()](#getSourceBitmap--) | Kaynak bitmap'i içeren bir tampon alır veya ayarlar; bu tamponun EMR\_PLGBLT kaydının sabit kısmıyla veya birbirleriyle bitişik olması gerekmez. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Kaynak bitmap'i içeren bir tampon alır veya ayarlar; bu tamponun EMR\_PLGBLT kaydının sabit kısmıyla veya birbirleriyle bitişik olması gerekmez. |
| [getMaskBitmap()](#getMaskBitmap--) | Maske bitmap'ini içeren bir tampon alır veya ayarlar; bu tamponun EMR\_PLGBLT kaydının sabit kısmıyla veya birbirleriyle bitişik olması gerekmez. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Maske bitmap'ini içeren bir tampon alır veya ayarlar; bu tamponun EMR\_PLGBLT kaydının sabit kısmıyla veya birbirleriyle bitişik olması gerekmez. |
### EmfPlgBlt(EmfRecord source) {#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPlgBlt(EmfRecord source)
```


Yeni bir `EmfPlgBlt` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hedefe yapılan çıktı için cihaz birimlerinde sınırlayıcı dikdörtgeni tanımlayan WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Hedefe yapılan çıktı için cihaz birimlerinde sınırlayıcı dikdörtgeni tanımlayan WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAptlDest() {#getAptlDest--}
```
public Point[] getAptlDest()
```


Üç WMF PointL nesnesinden oluşan bir dizi alır veya ayarlar ([MS-WMF] bölüm 2.2.2.15) ve bu dizi, blok aktarımı için bir paralelkenar hedef alanının üç köşesini belirtir. Kaynak dikdörtgenin sol‑üst köşesi bu dizideki ilk noktaya, sağ‑üst köşesi ikinci noktaya ve sol‑alt köşesi üçüncü noktaya eşlenir. Kaynak dikdörtgenin sağ‑alt köşesi, ilk üç noktadan (A, B ve C) vektör olarak ele alınarak hesaplanan paralelkenarın örtük dördüncü noktasına eşlenir. D = B + C A

**Returns:**
com.aspose.imaging.Point[]
### setAptlDest(Point[] value) {#setAptlDest-com.aspose.imaging.Point---}
```
public void setAptlDest(Point[] value)
```


Üç WMF PointL nesnesinden oluşan bir dizi alır veya ayarlar ([MS-WMF] bölüm 2.2.2.15) ve bu dizi, blok aktarımı için bir paralelkenar hedef alanının üç köşesini belirtir. Kaynak dikdörtgenin sol‑üst köşesi bu dizideki ilk noktaya, sağ‑üst köşesi ikinci noktaya ve sol‑alt köşesi üçüncü noktaya eşlenir. Kaynak dikdörtgenin sağ‑alt köşesi, ilk üç noktadan (A, B ve C) vektör olarak ele alınarak hesaplanan paralelkenarın örtük dördüncü noktasına eşlenir. D = B + C A

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

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

### getXFormSrc() {#getXFormSrc--}
```
public Matrix getXFormSrc()
```


Alır veya ayarlar, kaynak bitmap'e uygulanacak dünya uzayından sayfa uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28).

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXFormSrc(Matrix value) {#setXFormSrc-com.aspose.imaging.Matrix-}
```
public void setXFormSrc(Matrix value)
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


Kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi alır veya ayarlar ([MS-WMF] bölüm 2.2.2.8).

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


Kaynak bitmap'in arka plan rengini belirten bir WMF ColorRef nesnesi alır veya ayarlar ([MS-WMF] bölüm 2.2.2.8).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32‑bit işaretsiz bir tamsayı alır veya ayarlar. Bu değer DIBColors enumarasyonunda MUST olmalıdır.

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32‑bit işaretsiz bir tamsayı alır veya ayarlar. Bu değer DIBColors enumarasyonunda MUST olmalıdır.

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


Kaynak bitmap'i içeren bir tampon alır veya ayarlar; bu tamponun EMR\_PLGBLT kaydının sabit kısmıyla veya birbirleriyle bitişik olması gerekmez. Buna göre, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve MUST yok sayılmalıdır.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Kaynak bitmap'i içeren bir tampon alır veya ayarlar; bu tamponun EMR\_PLGBLT kaydının sabit kısmıyla veya birbirleriyle bitişik olması gerekmez. Buna göre, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve MUST yok sayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


Maske bitmap'ini içeren bir tampon alır veya ayarlar; bu tamponun EMR\_PLGBLT kaydının sabit kısmıyla veya birbirleriyle bitişik olması gerekmez. Buna göre, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve MUST yok sayılmalıdır.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


Maske bitmap'ini içeren bir tampon alır veya ayarlar; bu tamponun EMR\_PLGBLT kaydının sabit kısmıyla veya birbirleriyle bitişik olması gerekmez. Buna göre, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve MUST yok sayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

