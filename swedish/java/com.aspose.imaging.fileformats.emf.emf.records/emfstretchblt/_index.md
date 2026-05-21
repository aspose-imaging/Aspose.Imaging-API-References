---
title: "EmfStretchBlt"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_STRETCHBLT‑posten specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, eventuellt i kombination med ett penselmönster enligt en specificerad rasteroperation, som sträcker eller komprimerar utdata för att passa destinationsdimensionerna om så behövs."
type: docs
weight: 149
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchBlt extends EmfBitmapRecordType
```

EMR\_STRETCHBLT‑posten specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, eventuellt i kombination med ett penselmönster, enligt en angiven rasteroperation, och sträcker eller komprimerar utdata för att passa destinationsdimensionerna, om nödvändigt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfStretchBlt(EmfRecord source)](#EmfStretchBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfStretchBlt`. |
| [EmfStretchBlt()](#EmfStretchBlt--) | Initierar en ny instans av klassen `EmfStretchBlt`. |
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
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar rasteroperationskoden. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar rasteroperationskoden. |
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
| [getCxSrc()](#getCxSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln. |
| [setCxSrc(int value)](#setCxSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln. |
| [getCySrc()](#getCySrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln. |
| [setCySrc(int value)](#setCySrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln. |
| [getSourceBitmap()](#getSourceBitmap--) | Hämtar eller anger en buffer som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_STRETCHBLT‑posten. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger en buffer som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_STRETCHBLT‑posten. |
| [getSrcRect()](#getSrcRect--) | Hämtar eller anger källrektangeln. |
| [setSrcRect(Rectangle value)](#setSrcRect-com.aspose.imaging.Rectangle-) | Hämtar eller anger källrektangeln. |
| [getDestRect()](#getDestRect--) | Hämtar eller anger destinationsrektangeln. |
| [setDestRect(Rectangle value)](#setDestRect-com.aspose.imaging.Rectangle-) | Hämtar eller anger destinationsrektangeln. |
### EmfStretchBlt(EmfRecord source) {#EmfStretchBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchBlt(EmfRecord source)
```


Initierar en ny instans av klassen `EmfStretchBlt`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfStretchBlt() {#EmfStretchBlt--}
```
public EmfStretchBlt()
```


Initierar en ny instans av klassen `EmfStretchBlt`.

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

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar rasteroperationskoden. Denna kod definierar hur färgdata från källrektangeln ska kombineras med färgdata från destinationsrektangeln och eventuellt ett penselmönster för att uppnå den slutgiltiga färgen

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar rasteroperationskoden. Denna kod definierar hur färgdata från källrektangeln ska kombineras med färgdata från destinationsrektangeln och eventuellt ett penselmönster för att uppnå den slutgiltiga färgen

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


Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_STRETCHBLT‑posten. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_STRETCHBLT‑posten. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getSrcRect() {#getSrcRect--}
```
public Rectangle getSrcRect()
```


Hämtar eller anger källrektangeln.

Värde: Källrektangeln.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setSrcRect(Rectangle value) {#setSrcRect-com.aspose.imaging.Rectangle-}
```
public void setSrcRect(Rectangle value)
```


Hämtar eller anger källrektangeln.

Värde: Källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getDestRect() {#getDestRect--}
```
public Rectangle getDestRect()
```


Hämtar eller anger destinationsrektangeln.

Värde: Dest‑rektangeln.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setDestRect(Rectangle value) {#setDestRect-com.aspose.imaging.Rectangle-}
```
public void setDestRect(Rectangle value)
```


Hämtar eller anger destinationsrektangeln.

Värde: Dest‑rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

