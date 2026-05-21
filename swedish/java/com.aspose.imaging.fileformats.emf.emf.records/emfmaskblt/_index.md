---
title: "EmfMaskBlt"
second_title: "Aspose.Imaging för Java API-referens"
description: "Posten EMR_MASKBLT specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, valfritt i kombination med ett penselmönster och med tillämpning av en färgmaskbitmap enligt angivna förgrunds- och bakgrundsrasteroperationer."
type: docs
weight: 69
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfMaskBlt extends EmfBitmapRecordType
```

Den EMR_MASKBLT-posten specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, eventuellt i kombination med ett penselmönster och med tillämpning av en färgmaskbitmap, enligt angivna förgrunds‑ och bakgrundsrasteroperationer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfMaskBlt(EmfRecord source)](#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfMaskBlt`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationens avgränsningsrektangel i enhetsenheter. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationens avgränsningsrektangel i enhetsenheter. |
| [getXDest()](#getXDest--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [setXDest(int value)](#setXDest-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [getYDest()](#getYDest--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [setYDest(int value)](#setYDest-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [getCxDest()](#getCxDest--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på destinationsrektangeln. |
| [setCxDest(int value)](#setCxDest-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på destinationsrektangeln. |
| [getCyDest()](#getCyDest--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på destinationsrektangeln. |
| [setCyDest(int value)](#setCyDest-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på destinationsrektangeln. |
| [getRop4()](#getRop4--) | Hämtar eller anger en kvartär rasteroperation, som specificerar ternära rasteroperationer för förgrunds- och bakgrundsfärgerna i en bitmap. |
| [setRop4(EmfRop4 value)](#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-) | Hämtar eller anger en kvartär rasteroperation, som specificerar ternära rasteroperationer för förgrunds- och bakgrundsfärgerna i en bitmap. |
| [getXSrc()](#getXSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [setXSrc(int value)](#setXSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [getYSrc()](#getYSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [setYSrc(int value)](#setYSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [getXformSrc()](#getXformSrc--) | Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en världsrums‑till‑sidrymds‑transformering att tillämpa på källbitmapen. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en världsrums‑till‑sidrymds‑transformering att tillämpa på källbitmapen. |
| [getArgb32BkColorSrc()](#getArgb32BkColorSrc--) | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar bakgrundsfärgen för källbitmapen. |
| [setArgb32BkColorSrc(int value)](#setArgb32BkColorSrc-int-) | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar bakgrundsfärgen för källbitmapen. |
| [getUsageSrc()](#getUsageSrc--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. |
| [getXMask()](#getXMask--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av mask-bitmapen. |
| [setXMask(int value)](#setXMask-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av mask-bitmapen. |
| [getYMask()](#getYMask--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av mask-bitmapen. |
| [setYMask(int value)](#setYMask-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av mask-bitmapen. |
| [getUsageMask()](#getUsageMask--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i mask-bitmapens huvud ska tolkas. |
| [setUsageMask(int value)](#setUsageMask-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i mask-bitmapens huvud ska tolkas. |
| [getSourceBitmap()](#getSourceBitmap--) | Hämtar eller anger en buffert som innehåller källbitmaparna, vilka inte behöver vara sammanhängande med den fasta delen av EMR\_MASKBLT-posten eller med varandra. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger en buffert som innehåller källbitmaparna, vilka inte behöver vara sammanhängande med den fasta delen av EMR\_MASKBLT-posten eller med varandra. |
| [getMaskBitmap()](#getMaskBitmap--) | Hämtar eller anger en buffert som innehåller maskbitmaparna, vilka inte behöver vara sammanhängande med den fasta delen av EMR\_MASKBLT-posten eller med varandra. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger en buffert som innehåller maskbitmaparna, vilka inte behöver vara sammanhängande med den fasta delen av EMR\_MASKBLT-posten eller med varandra. |
### EmfMaskBlt(EmfRecord source) {#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMaskBlt(EmfRecord source)
```


Initierar en ny instans av klassen `EmfMaskBlt`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationens avgränsningsrektangel i enhetsenheter.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationens avgränsningsrektangel i enhetsenheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på destinationsrektangeln.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på destinationsrektangeln.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRop4() {#getRop4--}
```
public EmfRop4 getRop4()
```


Hämtar eller anger en kvartär rasteroperation, som specificerar ternära rasteroperationer för förgrunds- och bakgrundsfärgerna i en bitmap. Dessa värden definierar hur färgdata från källrektangeln ska kombineras med färgdata från destinationsrektangeln.

**Returns:**
[EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4)
### setRop4(EmfRop4 value) {#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-}
```
public void setRop4(EmfRop4 value)
```


Hämtar eller anger en kvartär rasteroperation, som specificerar ternära rasteroperationer för förgrunds- och bakgrundsfärgerna i en bitmap. Dessa värden definierar hur färgdata från källrektangeln ska kombineras med färgdata från destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4) |  |

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

### getXformSrc() {#getXformSrc--}
```
public Matrix getXformSrc()
```


Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en världsrums‑till‑sidrymds‑transformering att tillämpa på källbitmapen.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSrc(Matrix value) {#setXformSrc-com.aspose.imaging.Matrix-}
```
public void setXformSrc(Matrix value)
```


Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en världsrums‑till‑sidrymds‑transformering att tillämpa på källbitmapen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getArgb32BkColorSrc() {#getArgb32BkColorSrc--}
```
public int getArgb32BkColorSrc()
```


Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar bakgrundsfärgen för källbitmapen.

**Returns:**
int
### setArgb32BkColorSrc(int value) {#setArgb32BkColorSrc-int-}
```
public void setArgb32BkColorSrc(int value)
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


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. Detta värde MÅSTE finnas i DIBColors‑enumerationen (avsnitt 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. Detta värde MÅSTE finnas i DIBColors‑enumerationen (avsnitt 2.1.9).

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


Hämtar eller anger en buffert som innehåller källbitmaparna, vilka inte behöver vara sammanhängande med den fasta delen av EMR\_MASKBLT-posten eller med varandra. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger en buffert som innehåller källbitmaparna, vilka inte behöver vara sammanhängande med den fasta delen av EMR\_MASKBLT-posten eller med varandra. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


Hämtar eller anger en buffert som innehåller maskbitmaparna, vilka inte behöver vara sammanhängande med den fasta delen av EMR\_MASKBLT-posten eller med varandra. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger en buffert som innehåller maskbitmaparna, vilka inte behöver vara sammanhängande med den fasta delen av EMR\_MASKBLT-posten eller med varandra. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

