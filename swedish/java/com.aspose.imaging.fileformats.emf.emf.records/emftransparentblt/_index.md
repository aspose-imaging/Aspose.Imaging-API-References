---
title: "EmfTransparentBlt"
second_title: "Aspose.Imaging för Java API-referens"
description: "Posten EMR_TRANSPARENTBLT specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel där en angiven färg behandlas som transparent, och sträcker eller komprimerar utdata för att passa destinationsdimensionerna om nödvändigt."
type: docs
weight: 154
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfTransparentBlt extends EmfBitmapRecordType
```

EMR\_TRANSPARENTBLT‑posten specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, där en angiven färg behandlas som transparent, och sträcker eller komprimerar utdata för att passa destinationsdimensionerna, om nödvändigt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfTransparentBlt(EmfRecord source)](#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfTransparentBlt`. |
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
| [getTransparentArgb32Color()](#getTransparentArgb32Color--) | Hämtar eller anger ett WMF ColorRef‑objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar färgen i källbitmapen som ska behandlas som transparent. |
| [setTransparentArgb32Color(int value)](#setTransparentArgb32Color-int-) | Hämtar eller anger ett WMF ColorRef‑objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar färgen i källbitmapen som ska behandlas som transparent. |
| [getXSrc()](#getXSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [setXSrc(int value)](#setXSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [getYSrc()](#getYSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [setYSrc(int value)](#setYSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [getXformSrc()](#getXformSrc--) | Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en världsrums‑till‑sidrymds‑transformering att tillämpa på källbitmapen. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en världsrums‑till‑sidrymds‑transformering att tillämpa på källbitmapen. |
| [getSrcBkArgb32Color()](#getSrcBkArgb32Color--) | Hämtar eller anger ett WMF ColorRef‑objekt som specificerar bakgrundsfärgen för källbitmapen. |
| [setSrcBkArgb32Color(int value)](#setSrcBkArgb32Color-int-) | Hämtar eller anger ett WMF ColorRef‑objekt som specificerar bakgrundsfärgen för källbitmapen. |
| [getUsageSrc()](#getUsageSrc--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. |
| [getCxSrc()](#getCxSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln. |
| [setCxSrc(int value)](#setCxSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln. |
| [getCySrc()](#getCySrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln. |
| [setCySrc(int value)](#setCySrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln. |
| [getSourceBitmap()](#getSourceBitmap--) | Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av posten EMR\\_TRANSPARENTBLT. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av posten EMR\\_TRANSPARENTBLT. |
### EmfTransparentBlt(EmfRecord source) {#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfTransparentBlt(EmfRecord source)
```


Initierar en ny instans av klassen `EmfTransparentBlt`.

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

### getTransparentArgb32Color() {#getTransparentArgb32Color--}
```
public int getTransparentArgb32Color()
```


Hämtar eller anger ett WMF ColorRef‑objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar färgen i källbitmapen som ska behandlas som transparent.

**Returns:**
int
### setTransparentArgb32Color(int value) {#setTransparentArgb32Color-int-}
```
public void setTransparentArgb32Color(int value)
```


Hämtar eller anger ett WMF ColorRef‑objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar färgen i källbitmapen som ska behandlas som transparent.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

### getSrcBkArgb32Color() {#getSrcBkArgb32Color--}
```
public int getSrcBkArgb32Color()
```


Hämtar eller anger ett WMF ColorRef‑objekt som specificerar bakgrundsfärgen för källbitmapen.

**Returns:**
int
### setSrcBkArgb32Color(int value) {#setSrcBkArgb32Color-int-}
```
public void setSrcBkArgb32Color(int value)
```


Hämtar eller anger ett WMF ColorRef‑objekt som specificerar bakgrundsfärgen för källbitmapen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. Detta värde MÅSTE vara i DIBColors‑uppräkningen (avsnitt 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. Detta värde MÅSTE vara i DIBColors‑uppräkningen (avsnitt 2.1.9).

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

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av posten EMR\\_TRANSPARENTBLT. Följaktligen är fält i denna buffert som är märkta \"UndefinedSpace\" valfria och MÅSTE ignoreras.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av posten EMR\\_TRANSPARENTBLT. Följaktligen är fält i denna buffert som är märkta \"UndefinedSpace\" valfria och MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

