---
title: "EmfAlphaBlend"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_ALPHABLEND-posten specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel inklusive alfa‑transparentdata enligt en specificerad blandningsoperation."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfAlphaBlend extends EmfBitmapRecordType
```

EMR\_ALPHABLEND-posten specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, inklusive alfa‑transparentdata, enligt en specificerad blandningsoperation.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfAlphaBlend(EmfRecord source)](#EmfAlphaBlend-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfAlphaBlend`. |
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
| [getBlendFunction()](#getBlendFunction--) | Hämtar eller anger en struktur som specificerar blandningsoperationerna för käll- och destinationsbitmapar. |
| [setBlendFunction(EmfBlendFunction value)](#setBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) | Hämtar eller anger en struktur som specificerar blandningsoperationerna för käll- och destinationsbitmapar. |
| [getXSrc()](#getXSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [setXSrc(int value)](#setXSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [getYSrc()](#getYSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [setYSrc(int value)](#setYSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av källrektangeln. |
| [getXformSr()](#getXformSr--) | Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en världsrums‑till‑sidrymds‑transformering att tillämpa på källbitmapen. |
| [setXformSr(Matrix value)](#setXformSr-com.aspose.imaging.Matrix-) | Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en världsrums‑till‑sidrymds‑transformering att tillämpa på källbitmapen. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar bakgrundsfärgen för källbitmapen. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar bakgrundsfärgen för källbitmapen. |
| [getUsageSrc()](#getUsageSrc--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. |
| [getCxSrc()](#getCxSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln. |
| [setCxSrc(int value)](#setCxSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln. |
| [getCySrc()](#getCySrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln. |
| [setCySrc(int value)](#setCySrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln. |
| [getSourceBitmap()](#getSourceBitmap--) | Hämtar eller anger en buffer som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_ALPHABLEND-posten. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger en buffer som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_ALPHABLEND-posten. |
### EmfAlphaBlend(EmfRecord source) {#EmfAlphaBlend-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAlphaBlend(EmfRecord source)
```


Initierar en ny instans av klassen `EmfAlphaBlend`.

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


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på destinationsrektangeln. Detta värde MÅSTE vara större än noll.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på destinationsrektangeln. Detta värde MÅSTE vara större än noll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på destinationsrektangeln. Detta värde MÅSTE vara större än noll.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på destinationsrektangeln. Detta värde MÅSTE vara större än noll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBlendFunction() {#getBlendFunction--}
```
public EmfBlendFunction getBlendFunction()
```


Hämtar eller anger en struktur som specificerar blandningsoperationerna för käll- och destinationsbitmapar.

**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
### setBlendFunction(EmfBlendFunction value) {#setBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void setBlendFunction(EmfBlendFunction value)
```


Hämtar eller anger en struktur som specificerar blandningsoperationerna för käll- och destinationsbitmapar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

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

### getXformSr() {#getXformSr--}
```
public Matrix getXformSr()
```


Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en världsrums‑till‑sidrymds‑transformering att tillämpa på källbitmapen.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSr(Matrix value) {#setXformSr-com.aspose.imaging.Matrix-}
```
public void setXformSr(Matrix value)
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

Värde: Den 32-bitars ARGB-färgen

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar bakgrundsfärgen för källbitmapen.

Värde: Den 32-bitars ARGB-färgen

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


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln. Detta värde MÅSTE vara större än noll.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln. Detta värde MÅSTE vara större än noll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln. Detta värde MÅSTE vara större än noll.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln. Detta värde MÅSTE vara större än noll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Hämtar eller anger en buffer som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_ALPHABLEND-posten. Följaktligen är fält i denna buffer som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger en buffer som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_ALPHABLEND-posten. Följaktligen är fält i denna buffer som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

