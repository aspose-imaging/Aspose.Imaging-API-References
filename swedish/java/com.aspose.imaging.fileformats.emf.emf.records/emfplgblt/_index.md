---
title: "EmfPlgBlt"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_PLGBLT-posten specificerar en blocköverföring av pixlar från en källbitmap till ett destinationsparallelogram med tillämpning av en färgmaskbitmap."
type: docs
weight: 84
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfPlgBlt extends EmfBitmapRecordType
```

EMR\_PLGBLT‑posten specificerar en blocköverföring av pixlar från en källbitmap till ett destinationsparallellogram, med tillämpning av en färgmaskbitmap.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlgBlt(EmfRecord source)](#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfPlgBlt`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar den omgivande rektangeln, i enhetsenheter, för utskrift till destinationen. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar den omgivande rektangeln, i enhetsenheter, för utskrift till destinationen. |
| [getAptlDest()](#getAptlDest--) | Hämtar eller anger en array med tre WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar tre hörn i ett parallellogram‑målområde för blocköverföringen. |
| [setAptlDest(Point[] value)](#setAptlDest-com.aspose.imaging.Point---) | Hämtar eller anger en array med tre WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar tre hörn i ett parallellogram‑målområde för blocköverföringen. |
| [getXSrc()](#getXSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [setXSrc(int value)](#setXSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [getYSrc()](#getYSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [setYSrc(int value)](#setYSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [getCxSrc()](#getCxSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln. |
| [setCxSrc(int value)](#setCxSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln. |
| [getCySrc()](#getCySrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln. |
| [setCySrc(int value)](#setCySrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln. |
| [getXFormSrc()](#getXFormSrc--) | Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en världsrums‑till‑sidrymds‑transformering att tillämpa på källbitmapen. |
| [setXFormSrc(Matrix value)](#setXFormSrc-com.aspose.imaging.Matrix-) | Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en världsrums‑till‑sidrymds‑transformering att tillämpa på källbitmapen. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar bakgrundsfärgen för källbitmapen. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar bakgrundsfärgen för källbitmapen. |
| [getUsageSrc()](#getUsageSrc--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. |
| [getXMask()](#getXMask--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av mask-bitmapen. |
| [setXMask(int value)](#setXMask-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av mask-bitmapen. |
| [getYMask()](#getYMask--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av mask-bitmapen. |
| [setYMask(int value)](#setYMask-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av mask-bitmapen. |
| [getUsageMask()](#getUsageMask--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i mask-bitmapens huvud ska tolkas. |
| [setUsageMask(int value)](#setUsageMask-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i mask-bitmapens huvud ska tolkas. |
| [getSourceBitmap()](#getSourceBitmap--) | Hämtar eller anger en buffer som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_PLGBLT‑posten eller med varandra. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger en buffer som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_PLGBLT‑posten eller med varandra. |
| [getMaskBitmap()](#getMaskBitmap--) | Hämtar eller anger en buffer som innehåller maskbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_PLGBLT‑posten eller med varandra. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger en buffer som innehåller maskbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_PLGBLT‑posten eller med varandra. |
### EmfPlgBlt(EmfRecord source) {#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPlgBlt(EmfRecord source)
```


Initierar en ny instans av klassen `EmfPlgBlt`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar den omgivande rektangeln, i enhetsenheter, för utskrift till destinationen.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar den omgivande rektangeln, i enhetsenheter, för utskrift till destinationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAptlDest() {#getAptlDest--}
```
public Point[] getAptlDest()
```


Hämtar eller anger en array med tre WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar tre hörn i ett parallellogram‑målområde för blocköverföringen. Det övre vänstra hörnet av källrektangeln mappar till den första punkten i denna array, det övre högra hörnet till den andra punkten och det nedre vänstra hörnet till den tredje punkten. Det nedre högra hörnet av källrektangeln mappar till den implicita fjärde punkten i parallellogrammet, som beräknas från de tre första punkterna (A, B och C) genom att behandla dem som vektorer. D = B + C A

**Returns:**
com.aspose.imaging.Point[]
### setAptlDest(Point[] value) {#setAptlDest-com.aspose.imaging.Point---}
```
public void setAptlDest(Point[] value)
```


Hämtar eller anger en array med tre WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar tre hörn i ett parallellogram‑målområde för blocköverföringen. Det övre vänstra hörnet av källrektangeln mappar till den första punkten i denna array, det övre högra hörnet till den andra punkten och det nedre vänstra hörnet till den tredje punkten. Det nedre högra hörnet av källrektangeln mappar till den implicita fjärde punkten i parallellogrammet, som beräknas från de tre första punkterna (A, B och C) genom att behandla dem som vektorer. D = B + C A

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getXFormSrc() {#getXFormSrc--}
```
public Matrix getXFormSrc()
```


Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en världsrums‑till‑sidrymds‑transformering att tillämpa på källbitmapen.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXFormSrc(Matrix value) {#setXFormSrc-com.aspose.imaging.Matrix-}
```
public void setXFormSrc(Matrix value)
```


Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en världsrums‑till‑sidrymds‑transformering att tillämpa på källbitmapen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBkSrcArgb32Color() {#getBkSrcArgb32Color--}
```
public int getBkSrcArgb32Color()
```


Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar bakgrundsfärgen för källbitmapen.

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar bakgrundsfärgen för källbitmapen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. Detta värde MÅSTE vara i DIBColors‑enumerationen

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. Detta värde MÅSTE vara i DIBColors‑enumerationen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getXMask() {#getXMask--}
```
public int getXMask()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av mask-bitmapen.

**Returns:**
int
### setXMask(int value) {#setXMask-int-}
```
public void setXMask(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av mask-bitmapen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getYMask() {#getYMask--}
```
public int getYMask()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av mask-bitmapen.

**Returns:**
int
### setYMask(int value) {#setYMask-int-}
```
public void setYMask(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av mask-bitmapen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getUsageMask() {#getUsageMask--}
```
public int getUsageMask()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i mask-bitmapens huvud ska tolkas. Detta värde MÅSTE finnas i DIBColors‑enumerationen.

**Returns:**
int
### setUsageMask(int value) {#setUsageMask-int-}
```
public void setUsageMask(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i mask-bitmapens huvud ska tolkas. Detta värde MÅSTE finnas i DIBColors‑enumerationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Hämtar eller anger en buffer som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_PLGBLT‑posten eller med varandra. Följaktligen är fält i denna buffer som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger en buffer som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_PLGBLT‑posten eller med varandra. Följaktligen är fält i denna buffer som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


Hämtar eller anger en buffer som innehåller maskbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_PLGBLT‑posten eller med varandra. Följaktligen är fält i denna buffer som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger en buffer som innehåller maskbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_PLGBLT‑posten eller med varandra. Följaktligen är fält i denna buffer som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

