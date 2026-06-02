---
title: "EmfStretchDiBits"
second_title: "Aspose.Imaging för Java API-referens"
description: "Posten EMR_STRETCHDIBITS specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, eventuellt i kombination med ett penselmönster enligt en specificerad rasteroperation, och sträcker eller komprimerar utdata för att passa destinationsdimensionerna om så behövs."
type: docs
weight: 150
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchDiBits extends EmfBitmapRecordType
```

EMR\_STRETCHDIBITS‑posten specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, eventuellt i kombination med ett penselmönster, enligt en angiven rasteroperation, och sträcker eller komprimerar utdata för att passa destinationsdimensionerna, om nödvändigt.

Denna post stöder källbilder i JPEG‑ och PNG‑format. Komprimeringsfältet i källbitmapens huvud specificerar bildformatet. Om tecknen för källans och destinationens höjd‑ och breddfält skiljer sig, specificerar posten en spegelkopiering av källbitmapen till destinationen. Det vill säga, om cxSrc och cxDest har olika tecken anges en spegelbild av källbitmapen längs x‑axeln. Om cySrc och cyDest har olika tecken anges en spegelbild av källbitmapen längs y‑axeln.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfStretchDiBits(EmfRecord source)](#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfStretchDiBits`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationens avgränsningsrektangel i enhetsenheter. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationens avgränsningsrektangel i enhetsenheter. |
| [getXDest()](#getXDest--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [setXDest(int value)](#setXDest-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [getYDest()](#getYDest--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [setYDest(int value)](#setYDest-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [getXSrc()](#getXSrc--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar x‑koordinaten i pixlar för det övre vänstra hörnet av källrektangeln. |
| [setXSrc(int value)](#setXSrc-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar x‑koordinaten i pixlar för det övre vänstra hörnet av källrektangeln. |
| [getYSrc()](#getYSrc--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar y‑koordinaten i pixlar för det övre vänstra hörnet av källrektangeln. |
| [setYSrc(int value)](#setYSrc-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar y‑koordinaten i pixlar för det övre vänstra hörnet av källrektangeln. |
| [getCxSrc()](#getCxSrc--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar bredden i pixlar för källrektangeln. |
| [setCxSrc(int value)](#setCxSrc-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar bredden i pixlar för källrektangeln. |
| [getCySrc()](#getCySrc--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar höjden i pixlar för källrektangeln. |
| [setCySrc(int value)](#setCySrc-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar höjden i pixlar för källrektangeln. |
| [getUsageSrc()](#getUsageSrc--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar en rasteroperationskod. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar en rasteroperationskod. |
| [getCxDest()](#getCxDest--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på destinationsrektangeln. |
| [setCxDest(int value)](#setCxDest-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på destinationsrektangeln. |
| [getCyDest()](#getCyDest--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på destinationsrektangeln. |
| [setCyDest(int value)](#setCyDest-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på destinationsrektangeln. |
| [getSourceBitmap()](#getSourceBitmap--) | Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av posten EMR\_STRETCHDIBITS. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av posten EMR\_STRETCHDIBITS. |
### EmfStretchDiBits(EmfRecord source) {#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchDiBits(EmfRecord source)
```


Initierar en ny instans av klassen `EmfStretchDiBits`.

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

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar x‑koordinaten i pixlar för det övre vänstra hörnet av källrektangeln.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar x‑koordinaten i pixlar för det övre vänstra hörnet av källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar y‑koordinaten i pixlar för det övre vänstra hörnet av källrektangeln.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar y‑koordinaten i pixlar för det övre vänstra hörnet av källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar bredden i pixlar för källrektangeln.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar bredden i pixlar för källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar höjden i pixlar för källrektangeln.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar höjden i pixlar för källrektangeln.

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

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar en rasteroperationskod. Dessa koder definierar hur färgdata från källrektangeln ska kombineras med färgdata från destinationsrektangeln och eventuellt ett penselmönster för att uppnå den slutgiltiga färgen.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar en rasteroperationskod. Dessa koder definierar hur färgdata från källrektangeln ska kombineras med färgdata från destinationsrektangeln och eventuellt ett penselmönster för att uppnå den slutgiltiga färgen.

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

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av posten EMR\_STRETCHDIBITS. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av posten EMR\_STRETCHDIBITS. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

